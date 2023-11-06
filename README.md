# 2105634_AI
Program that takes an image as its input and generates the same image using N number of squares using Genetic Algorithm.

To run the code you provided, follow these steps:

1. Install the following Python packages:
    * Pillow
    * random
    * itertools
    * math
    * os

2. Save the code as a Python file, such as `image_regeneration.py`.

3. Open a terminal window and navigate to the directory where you saved the code file.

4. Run the following command to start the genetic algorithm:

```python
python image_regeneration.py
```

5. The genetic algorithm will start running and will periodically display the current generation number and the fitness score of the fittest individual.

6. The genetic algorithm will terminate when the fittest individual has reached the target fitness score or a maximum number of generations has been reached.

7. Once the genetic algorithm has terminated, you can view the regenerated image by opening the `fittest.txt` file.

Here is an example of how to run the code on a Linux or macOS system:

```
cd path/to/code
python image_regeneration.py
```

Here is an example of how to run the code on a Windows system:

```
cd path\to\code
python image_regeneration.py
```

**Tips:**

* You can adjust the genetic algorithm parameters, such as the population size, mutation rate, and crossover operator, by editing the `setup()` function in the code.
* You can also change the target fitness score by editing the `fitness_score()` function.
* If you want to view the regenerated image after each generation, you can uncomment the following line in the `perform_natural_selection()` function:

```python
vec_to_image(fittest,original_image)
```


