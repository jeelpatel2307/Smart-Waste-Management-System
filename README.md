# Smart Waste Management System

## Overview

This project implements a Smart Waste Management System in Java. The system optimizes waste collection routes to minimize time and resources spent on waste collection. It provides functionalities to manage waste bins, create waste collection routes, and optimize these routes for efficient waste collection.

## Features

- **Waste Bin Management:** Users can add, remove, and update waste bins' status (full or empty).
- **Waste Collection Route Optimization:** The system optimizes waste collection routes to reduce collection time and resources.
- **Location-Based Services:** Waste bins are associated with geographic coordinates, allowing for spatial optimization of waste collection routes.

## Getting Started

1. **Clone the Repository:**
    
    ```bash
    git clone <https://github.com/yourusername/smart-waste-management.git>
    
    ```
    
2. **Compile and Run:**
    
    ```bash
    cd smart-waste-management
    javac SmartWasteManagementSystem.java
    java SmartWasteManagementSystem
    
    ```
    
3. **Add Waste Bins:**
    
    Update the `main` method in `SmartWasteManagementSystem.java` to add waste bins with their respective coordinates.
    
4. **Optimize Waste Collection Routes:**
    
    Run the program to optimize waste collection routes based on the added waste bins.
    

## Usage

1. **Add Waste Bins:**
    
    ```java
    WasteBin bin1 = new WasteBin("1", 42.3601, -71.0589);
    WasteBin bin2 = new WasteBin("2", 42.3662, -71.0621);
    WasteManagementSystem.addBin(bin1);
    WasteManagementSystem.addBin(bin2);
    
    ```
    
2. **Optimize Routes:**
    
    ```java
    List<WasteCollectionRoute> routes = WasteManagementSystem.optimizeRoutes();
    
    ```
    
3. **Display Routes:**
    
    Display the optimized routes obtained from the system.
    

## Contributors

- Jeel patel
