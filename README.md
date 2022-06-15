# optuna-visualization-regression-tests

## How to run

```
$ pip install -r requirements.txt
$ python visual_regression_tests.py plot_optimization_history --output-dir /tmp/foo
Generated to: /tmp/foo/index.html
```

## Example Output

### `plot_optimization_history()`

<img width="1715" alt="plot_optimization_history" src="https://user-images.githubusercontent.com/5564044/173838248-8f9599ec-c7cb-482c-9fd3-be6c856520d0.png">

### `plot_slice()`

<img width="1715" alt="plot_slice" src="https://user-images.githubusercontent.com/5564044/173838319-24433136-bd59-47d5-afdb-2694aafe354d.png">

### `plot_pareto_front()`

<img width="1715" alt="plot_pareto_front" src="https://user-images.githubusercontent.com/5564044/173838426-34f87856-411f-41e9-8e0f-dee5b6329a45.png">

### `plot_contour()`

<img width="1715" alt="plot_contour" src="https://user-images.githubusercontent.com/5564044/173839582-b22da40d-34f0-40c6-baf9-c2e541b7f9a7.png">

### `plot_edf()`

### `plot_intermediate_value()`

### `plot_parallel_coordinate()`

### `plot_param_importances()`

## CLI Options

```
$ python visual_regression_tests.py --help
usage: visual_regression_tests.py [-h] [--output-dir OUTPUT_DIR] [--width WIDTH] [--height HEIGHT] [--relpath]

optional arguments:
  -h, --help            show this help message and exit
  --output-dir OUTPUT_DIR
                        output directory (default: tmp)
  --width WIDTH         plot width (default: 800)
  --height HEIGHT       plot height (default: 600)
```
