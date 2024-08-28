# CAS_Agent_Based_Modeling
A Complex Adaptive System - Agent-Based Model (implemented in NetLogo), that simulated and observed the systems-level impacts of the interactions between Banks and Depositors in a Banking Eco-system.

# Overview
An Agent-Based Modeling of Deposit Interest Rate & Bank Stability: Depositors’ Behavior. The Agent-Based Model attempted to observe the systems-level impacts of the interactions between Banks and Depositors in a Banking Eco-system.

Project Rationale: Observing the Interactions of Banks and Depositors – Using Agent-Based Modeling (in NetLogo) Technique.

Covered a review of what, why and who will use the system. The model can help to gain an informed understanding of the complex interactions between.

Domain Review – Context & Background:
At a micro-level, the Silicon Valley Bank (SVB)’s failure is shown as an example of a dimension of the banking industry being a Complex System: small change(s) in some drivers --> much bigger system-level impacts.

Model Features & Key Considerations:
Covers the environment chosen – open, the description of agents and their attributes. Behavior of the key elements, and the procedures underlying the simulation considered.

Model Design and Results:
Some emergent properties at the aggregate / banking sector level highlighted.
The impact of bank stability factor, used by depositors to calibrate their risk-aversion coefficient, on the share of the wallet deposited at system-wide level, was observed.


# Domain Review
<img width="478" alt="image" src="https://github.com/user-attachments/assets/b3179fc3-5455-40d5-b7b1-c1fe1664f5fe">

# Model Design and Key Considerations
<img width="478" alt="image" src="https://github.com/user-attachments/assets/7f879df0-5402-4a47-8a90-ec2624c144f1">

# Model Design and Results
<img width="478" alt="image" src="https://github.com/user-attachments/assets/a96bd083-d4a7-4cdb-a3de-c053e7fcbdc7">

# Results Review 

<img width="478" alt="image" src="https://github.com/user-attachments/assets/1457713e-47a2-4713-a064-6b8ce4dda16c">

# Code

What Is It: The model, named here simply as the Deposit Interest-Stability Model (DISM), simulates the interactions of depositors and banks, where deposit and withdrawal decisions are principally influenced by a bank’s deposit interest rate, and a bank’s stability factor.

How It Works: Depositors choose where and when to deposit or withdraw their money. Banks accept deposits, honor withdrawal requests, update the total deposits held at their bank. Banks set risk appetite via investment mix (gilt & bonds/loans/other).

Key Features: Deposit-money and withdraw-money procedures – set as random amount of money to withdraw, subject to being no more than the depositor has available at a bank.

# Program Information

WHAT IS IT: This program models the deposit and withdrawal interactions of depositors and their banks in a typical banking system. The model simulates the interactions of depositors and banks, where deposit and withdrawal decisions are principally influenced by a bank’s deposit interest rate, and a bank’s stability factor.

It is a relatively simple Agent-Based Model, with 2 agents interacting based on a handful of procedures and rules. Deposit and withdrawal decisions are principally influenced by a bank’s deposit interest rate, and a bank’s stability factor.

HOW DOES IT WORK: In each iteration/time step, depositors choose where and when to deposit or withdraw their money. Banks accept deposits, honor withdrawal requests, update the total deposits held at their bank. Banks set risk appetite via investment mix (gilt & bonds/loans/other).

The system consists of 200 depositors (represented by ”person” turtles), and 5 banks (represented by “houses”)
Depositor color (green) set based on money, from 0 to 1000. Deep-green = more money on this scale.

Deposit-interest-rate is random-float from 1% to 5%; Banks’ Stability values are randomly set between 0 and 100 for each iteration/time step. Deposit-money amount: set randomly subject to the balance that a depositor has available at a bank.

Deposit-money amount: [(deposit-interest-rate * 100) - ($(money – amount) * (1- risk-aversion))].

SET-UP & GO DETAILS: After set up, to operate time steps use the "Go" in a single click and stop, rather than let it run indefinitely. Emergent behaviors of the agents (Depositors) and the Banks can be observed after every iteration/tick.

# Limitations
Limitations include – limited literature review coupled with limited review and exploration of several aspects of the model, and an in-depth study of the domain to help, not least in testing, validation and verification of the model.

# Next Steps
Next Steps model should be validated and verified to ensure robustness. The model is a relatively simple model looking only at deposit decision drivers. Other factors are likely to be at play, even at the fractal level.

# Languages:
Netlogo – 80% - NetLogo is a multi-agent programmable modeling environment, authored by Uri Wilensky, and developed by the Northwestern's Center for Connected Learning and Computer-Based Modeling (CCL).

Microsoft PowerPoint – 10%

Microsoft Excel – 5%

Tableau – 5%
