## Exercise 01: Linear Regression

### Young’s Modulus Estimation

This exercise provides a hands-on introduction to linear regression and its application in determining the Young’s modulus of a material from experimental stress–strain data. It aims to bridge theoretical understanding of regression with a real-world engineering context.

#### The exercise is structured in three parts:

1. Data exploration and visualization

    Learn to load and inspect experimental stress–strain data using pandas and numpy.
    Visualize the stress–strain relationship using Plotly to identify the linear (elastic) region.
    Define a cutoff strain value to isolate the region used for fitting.

2. Regression and model fitting

    Use scikit-learn’s LinearRegression to perform a simple linear fit on the elastic region of the data.
    Compute the slope of the fitted line, which corresponds to the Young’s modulus.
    Evaluate the model performance using Mean Squared Error (MSE) and visualize the linear fit.

3. Material comparison and interpretation

    Compare the experimentally obtained modulus with reference values (Steel, Aluminum, Titanium), all in GPa.
    Quantify the relative error and identify which material your sample most closely resembles.
    Reflect on possible deviations due to factors such as grain size, microstructure, and experimental uncertainty.