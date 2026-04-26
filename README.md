# EXP-1
EXPT NO: 1	VERIFICATION OF KIRCHHOFF’S LAWS
AIM
a.   To verify Kirchhoff’s Voltage Law (KVL) for the given circuit. 
b.   To verify Kirchhoff’s Current Law (KCL) for the given circuits.

APPARATUS REQUIRED:
S.No.	Components	Range	Quantity
1	Resistor	1kΩ	3
2	Voltmeter (DC)	0-30V	3
3	Ammeter (DC)	(0-200)mA	3
4	Bread Board		1
5	Regulated Power Supply	(0-30)V	1
6	Connecting wires		As required

THEORY:
KVL: Kirchhoff's voltage law states that the sum of the voltage differences around any closed loop in a circuit must be zero. A loop in a circuit is any path that ends at the same point at which it starts.
KCL:
Kirchhoff's Current Law (KCL) Kirchhoff's Current Law states that the algebraic sum of the currents entering and leaving a node is equal to zero. By convention, currents entering the node are positive, and those leaving a node are negative


PROCEDURE:
a.   KVL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the voltmeter connected across each resistor.
7.   Take readings for different values of input voltage and tabulate them.


b.  KCL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the ammeter connected to each resistor.
7.   Take readings for different values of input voltage and tabulate them. 
CIRCUIT DIAGRAM:

CIRCUIT DIAGRAM:


a.   KVL:

 <img width="1511" height="828" alt="Screenshot 2026-04-25 115844" src="https://github.com/user-attachments/assets/1ff7f93c-3ac2-4a15-afcb-4cab24a4a15a" />



b.  KCL:
 
 <img width="1044" height="544" alt="image" src="https://github.com/user-attachments/assets/b631e1af-fcfd-42c3-8387-5839e3334625" />


Calculation:

a.   KVL:
 
## Circuit Calculation

$$
V = V_{30\Omega} + V_{50\Omega} + V_{100\Omega}
$$

$$
100 = IR_1 + IR_2 + IR_3
$$

$$
R_{eq} = R_1 + R_2 + R_3 = 180\Omega
$$

$$
I = \frac{V}{R_{eq}} = \frac{100}{180} = 0.556A
$$

$$
V_1 = IR_1 = 0.556 \times 30 = 16.68V
$$

$$
V_2 = IR_2 = 0.556 \times 50 = 27.8V
$$

$$
V_3 = IR_3 = 0.556 \times 100 = 55.6V
$$



b.  KCL:

### b. KCL

$$
i_{30\Omega} = i_{50\Omega} + i_{100\Omega}
$$

$$
i_{30\Omega} = \frac{100 - V}{30}
$$

$$
i_{50\Omega} = \frac{V}{50}
$$

$$
i_{100\Omega} = \frac{V}{100}
$$

$$
\frac{100 - V}{30} = \frac{V}{50} + \frac{V}{100}
$$

$$
\frac{100 - V}{30} = \frac{2V}{100} + \frac{V}{100}
$$

$$
\frac{100 - V}{30} = \frac{3V}{100}
$$

$$
1000 - 10V = 9V
$$

$$
19V = 1000
$$

$$
V = \frac{1000}{19} = 52.63V
$$

$$
i_{30\Omega} = \frac{100 - 52.63}{30} = 1.58A
$$

$$
i_{50\Omega} = \frac{52.63}{50} = 1.05A
$$

$$
i_{100\Omega} = \frac{52.63}{100} = 0.53A
$$

Tabulation:

a.   KVL:

 ### a. KVL

| KVL        | Source(V) | V30Ω  | V50Ω | V100Ω | V30Ω + V50Ω + V100Ω |
|------------|----------|-------|------|-------|----------------------|
| Theoretical| 100      | 16.68V| 27.8V| 55.6V | 100.05V             |
| Practical  | 100      | 16.7V | 27.8V| 55.6V | 100.1V              |


b.  KCL:

### b. KCL

| KCL        | I30Ω | I50Ω | I100Ω | VA     |
|------------|------|------|-------|--------|
| Theoretical| 1.58A| 1.05A| 0.53A | 52.63V |
| Practical  | 1.58A| 1.05A| 0.53A | 52.6V  |

RESULT:

Thus, for the given circuit, Kirchhoff’s Laws, (a) KVL and (b) KCL are proved.
