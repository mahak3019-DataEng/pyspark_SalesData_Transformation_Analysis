# PySpark Transformation on Sales Data with Docker Integration

This project demonstrates the use of PySpark for transforming sales data, and the setup of a PySpark environment using a Docker image with Jupyter Lab.

## Overview

The project involves the following key components:
- **PySpark Transformations:** Performing data transformations on sales data using PySpark.
- **Docker Integration:** Running a Jupyter Lab environment with PySpark support inside a Docker container.

## Getting Started

Follow these steps to set up the PySpark environment and run the transformations:

### 1. Install Jupyter Lab

First, ensure you have Jupyter Lab installed. Run the following command:

```bash
pip install jupyterlab

### 2. Pull the Jupyter PySpark Docker Image
Retrieve the Docker image for Jupyter Lab with PySpark:

```bash
docker pull jupyter/pyspark-notebook

### 3. Run the Docker Container
Start a Docker container with the Jupyter Lab image:

```bash
docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook