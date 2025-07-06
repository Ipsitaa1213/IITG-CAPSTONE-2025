# IITG-CAPSTONE-2025

Project Description
Title: Dynamic Pricing System for Urban Parking Lots
Type: Capstone Project – Summer Analytics 2025
Conducted by: Consulting & Analytics Club, IIT Guwahati
Powered by: Pathway
I developed a real-time dynamic pricing engine to improve utilization of urban parking spaces. The project was based on data from 14 parking lots over 73 days, with pricing updated across 18 time intervals each day. My goal was to create a pricing system that responded smoothly to changing demand conditions like occupancy, traffic, queue length, special events, and vehicle type.
I implemented three models. Model 1 was a linear baseline that increased prices proportionally with occupancy. Model 2 used a demand function that incorporated queue length, traffic congestion, special day indicators, and weighted vehicle types. Model 3 introduced competitive pricing by comparing nearby parking lot prices using geographic proximity calculated through the Haversine formula.
To simulate real-time pricing, I used Pathway’s replay_csv() function to ingest and process data streams at a controlled rate. I applied a daily tumbling window to aggregate demand patterns and compute dynamic prices.
I visualized the pricing output using Bokeh and Panel to create an interactive dashboard that displayed the price evolution in real time.
Tools used included Python, Pandas, NumPy, Matplotlib, Bokeh, Panel, and Pathway. All development and testing were done in Google Colab.
Key outcomes included the creation of three demand-aware models, a real-time processing pipeline, and a live visualization dashboard. The system ensures that price changes are explainable, responsive, and bounded within realistic limits.
