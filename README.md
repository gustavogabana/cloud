# AWS Cloud Practioner Essentials Main Topics

## What is Cloud Computing?

Cloud computing is on-demand delivery of IT resources over the internet with pay-as-you-go pricing.

## Benefits of Cloud Computing

- Trade fixed expenses for variable expenses with pay-as-you-go
- Benefit from massive economies of scale (price is usually cheaper)
- Stop guessing capacity, you control it
- Increase speed and agility
- No need to run and maintain datacenters or on-premise hardware
- Go global fast (deploy your app in any country)

## Introduction to Global Infrastructure

High availability ensures that the application remains accessible with little to no interruption.
Fault tolerance is designed to keep the app running even if one or more components fail. It's building resilience in every layer so a single failure doesn't bring down everything.

These goals is the reason why AWS operates in regions as close to customers as possible.

### AZs

Within each region, AWS has Availability Zones (AZs). There are three or more AZs per region for redundancy. Within each AZ, there is one or more datacenter with redundant power, connectivity, and networking.

## Shared Responsability Model

Both the client and AWS are responsible to ensure that the application and the AWS resources that it use are secure.

AWS is responsible for security on the cloud, the customer is responsible for security in the cloud.
