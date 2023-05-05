# s23-statistics-assignment-2

## Simulated Annealing

Maxim Pryanikov  
m.pryanikov@innopolis.university  
@m4ximpr

### Run
```bash
git clone git@github.com:maxim-pr/s23-statistics-assignment-2.git
pip install -r requirements.txt
jupyter notebook Task2.ipynb
```

In this assignment we used Simulated Annealing to solve the Travelling Salesman problem on the example of 30 Russian cities.
[Cities](media/cities.png)
[Paths](media/path.png) 

#### Fast cooling
[Distance convergence](media/fast-cooling/distance-convergence.png)  
[Temperature convergence](media/fast-cooling/temperature-convergence.png)  
[Animation](media/fast-cooling/video.mp4)  

#### Middle cooling
[Distance convergence](media/middle-cooling/distance-convergence.png)  
[Temperature convergence](media/middle-cooling/temperature-convergence.png)  
[Animation](media/middle-cooling/video.mp4)  

#### Slow cooling
[Distance convergence](media/slow-cooling/distance-convergence.png)  
[Temperature convergence](media/slow-cooling/temperature-convergence.png)  
[Animation](media/slow-cooling/video.mp4)  

### Conclusion
- Different cooling rates affect the speed of convergence.  
- Slow cooling yields best result out of all the tried cooling rates.