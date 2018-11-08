### Dash Renderer - The Dash Frontend

This Dash Renderer is a modular front-end for [Dash](https://plot.ly/products/dash). To learn more about Dash, [view the user guide](https://plot.ly/dash).

[![CircleCI](https://circleci.com/gh/plotly/dash-renderer.svg?style=svg)](https://circleci.com/gh/plotly/dash-renderer)



See Original project [here](https://github.com/plotly/dash-renderer)

This Fork is to add JWT support for Dash:

- On client side, add an Authentication header with Bearer JWTToken with every POST and GET request to server
- On server side, add methods to allow user to request a JWTToken as well as authenticate the received JWTToken before sending data to client side.
