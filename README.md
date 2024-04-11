# Hospital Resource Allocation using Agent-Based modelling

## Context

In viral crises, such as the  COVID-19 scenario, hospital resources, such as hospital accommodations and staff, are limited. Viruses can spread as patients travel from one station in the hospital to another, worsening the situation.

## Objective

The primary goal of this project is to investigate and implement an efficient and secure allocation strategy for hospital resources and personnel. The focus is on maximizing patient recovery while simultaneously minimizing the transmission of viruses among patients.

## Methodology

Our intention is to develop a simulation framework for hospital operations. In this framework, we aim to represent hospital processes as Dynamical Systems, allowing for the customization of waiting times and process durations based on the specific characteristics of each hospital. The simulation will incorporate Agent-Based Modeling (ABM) to depict patients and staff, enabling the adjustment of transmission rates for viral infections within the model.

### Experiment Parameters
* Time spent in entrance: 10
* Time spent in pharmacy: 15
* Time spent in registration: 20
* Time spent in waiting area: 60
* Size of entrance: (20,10)
* Size of pharmacy: (8,8)
* Size of registration: (5,5)
* Size of waiting area: (10,10)
* Probability of patient arrival: 0.1
* Probability of infected patient arrival: 0.1
* Probability of transmission on contact: 0.1

### Experiment Hyperparameters
* No. of experiments per set of parameters: 100
* No. of epochs per experiment: 1000

## Conclusion

This project employs a combination of Dynamical Systems and Agent-Based Modeling to simulate hospital processes and personnel behaviors, with a focus on optimizing resource allocation in the context of viral outbreaks. The experimentation includes a detailed exploration of various parameters and hyperparameters to ensure a robust and adaptable simulation model. The ultimate aim is to provide hospitals with a tool that facilitates strategic decision-making for resource allocation, thereby enhancing both patient care and infection control.
