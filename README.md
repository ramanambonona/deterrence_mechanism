# On The Economic of Law Enforcement : Harm Repairing and Deterrence Mechanisms
In the context of illegal activity resulting in damage to victims, it is appropriate first to repair the harm and then to apply punishment. However, it is impossible to proceed with the compensation of damages if the perpetrator of the prejudicial act is not detected. Thereafter, the legal procedure of applying the punishment succeeds the compensation of damage. This article aims at combining the civil procedure of compensation (tort procedure) and the criminal procedure (legal procedure) of enforcement of the law.

In order to achieve our goal of repairing damages while deterring illegal activities, we use the following assumptions :

- Repair harm is impossible without preceding detection
- Punishment cannot be applied without detection
- Conviction is a detection-dependent event
- We release of the assumption that probability of detection and probability of conviction are the same
- The compensation of the damage can be total if detection is certain

We note by\
$b$ : the monetary benefit\
$h$ : harm\
$s$ : fine\
$p$ : probability of arrest\
$q$ : probability of conviction

A priori, we have the intuition that 

$$b = q (h +s)$$
if we set $S = h +s$, such that 
$\bar{S}= h +\bar{s}$ and $\underline{S} = h +\underline{s}$
if the offender is rich, we apply $\bar{S}$, and if the offender is poor, we use $\underline{S}$

The expected utility of the offender is written

$$ EU_{p,q} = (1-p)(1-q)b + (b-h)p(1-q) + q(b-h-s)$$

After simplifying,

$$ EU_{p,q} = b - qs + h(p(1-q) +q)$$

Note that $b-qs$ is the expected benefit and $h(p(1-p)+q)$ the expected damage.

## Proposition 1
If detection is uncertain, conviction is also uncertain because, since the two events are dependent, the offender anticipates a monetary benefit b
## Proof 1
As $p =0$, $q$ must necessarily be equal to zero because the two events are dependent
$E_{0,0} = b$


## Proposition 2
If the arrest is certain, the harm is repaired and whatever the value of the probability of conviction, we obtain the canonial form of the Becker $b-qs$ deterrence model
## Proof 2
If $p=1$, for any $q$, $EU_{1,q}=b-qs+h((1-q)+q)$, so $E_{1,q} = b-qs$

This means that conviction depends on detection. Law enforcer can only punish if the offender is arrested. So to satisfy the condition of deterrence and damage compensation and before applying the punishment, it is necessary that $p=1$. In other words, it is necessary that the arrest be certain so that the damage is compensated for in order to subsequently apply the punishment.

## Proposition 3
If the detection is at the optimum, the damage is eliminated by acting on $p$, we obtain $h = 0$.
## Proof 3
By acting on $p$, $\frac{\partial E}{\partial p}=0$  $h((1-q)+q)=0$ $\Longrightarrow h=0$.

