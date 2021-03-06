# SE2811 Group 4:

## Design Pattern: Thread Pool
### Design Pattern Description:
In our design there is a queue holding the new tasks for the pool, the pool itself which contains the currently running tasks, and the completed collection of tasks. Tasks in the pool are run concurrently.

### Project Description:
Our project will calculate the factors of a large all number, by using a thread pool and distributing the workload among the threads.
Each thread will be given a proportional amount of the total numbers to go through, based on the large number entered, meaning that each thread will calculate the factors for a particular range. 
Once the task is completed it will keep all of its results in a hash map for easy access, and the entire task will then be stored with a collection of the other completed tasks. This will allow for the re-use of tasks.

### GUI:
GUI will use Services to show progression with progress bars for each task.

### Team Members: (Alphabetically)
* Mitchell Mahnke
* Alex Moran
* Benjamin Pasten

### Presentation Outline:
1. Title Slide
2. Design Pattern Description
3. Our Project Description
4. Our Project Results

### Remaining Work Assignments:
* Mitchell Mahnke - Use services to display progress of threads with JavaFX.
* Alex Moran - Finish the Power Point Presentation, assist with implementation of pool and concurrent threads running in the pool.
* Benjamin Pasten - Work on storing the results of the factored numbers in a thread safe way, so that they may be used again.
