# ee8744---homework-3-solved
**TO GET THIS SOLUTION VISIT:** [EE8744 – Homework 3 Solved](https://www.ankitcodinghub.com/product/ee8744-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117084&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE8744 - Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Problem 1. Consider a balanced, three-phase capacitive circuit, where each leg has Capacitance C with effective series resistance, R. Denote the voltages and currents across the RC combination as va, vb, vc and ia, ib, ic. Derive corresponding expressions for the d and q-axis components.

Problem 2. The dynamics of a linear balanced-three phase inductive circuit in the αβ domain are given by:

. (1)

What are the corresponding dynamics in the abc domain?

ωit

(2)

it.

√

Implicit in the definitions above is that the amplitudes of the two voltages are denoted by√ 2E,

2V ; and frequencies are denoted by ωe, ωi. In what follows, we will also find it useful to define corresponding voltage phase angles by θe = ωet, θi = ωit, respectively. To facilitate analysis, we will reference the angle difference δ = θi − θe in subsequent developments. The inverter output currents (referred interchangeably as line currents) in the αβ reference frame are denoted by iα,iβ, respectively, and in the local dq reference frame by id,iq, respectively. Figure 1 illustrates several of the quantities referenced above.

Now consider the implementation of droop control depicted in Fig. 2. At the core are the following linear trade-offs:

(3a)

, (3b)

where P,Q are filtered active- and reactive-power values measured at the inverter terminals (we discuss this shortly), and mq,mp are determined by the voltage- and frequency-droop specifications. For instance, if we assume a 5% voltage droop and 0.5Hz frequency droop while the inverters are running at rated power Srated, then it follows that mq = 0.05Vnom/Srated and mp = 2π0.5Hz/Srated. To reject double-frequency pulsating components that arise from imbalances and switching ripple (which are inescapable in practical systems) from the power calculations, a low-pass (LP) filter is required. In this problem, we will assume a first-order LP filter. The dynamics of the filtered activeand reactive-power, denoted by P and Q, respectively, can be written as

P˙ = ωc(P − P), Q˙ = ωc(Q − Q), (4)

where ωc is the cut-off frequency which typically ranges from several Hz to tens of Hz. In general, the LP filter will hinder control responsiveness as the filtered quantities are leveraged inside the droop controller. Therefore, the selection of the cut-off frequency, ωc, is an important design choice and it presents an important trade-off between power-filtering performance and system-transient response. With these definitions in place, we see that the dynamics of the terminal voltage amplitude V and angle θi in (3) are given by:

, (5a)

(5b) In subsequent developments, we will express the phase dynamics with the power angle δ as follows

δ˙ = ωnom − ωe − mp(P − P?). (6)

Part (i). Let ed,eq correspond to the dq reference-frame representations of the external network voltage eabc. Using an appropriate reference transformation, express ed, eq as a function of δ and E. Part (ii) Derive the state-space model for the dynamics of id, iq with inputs ed, eq.

Part (iii) Show that the instantaneous active and reactive power at the inverter terminals P, Q are given by

. (7)

Part (iv) List down the dynamical equations for id, iq, V , δ, and P clearly indicating all parameters and inputs. This fifth-order model captures all dynamics of the GFM inverter with droop control. Note that the filtered reactive power is linearly related to the terminal voltage, and therefore, while we can recover it’s dynamics, we will not carry it forward in the analysis.

Figure 1: Illustrating frequently referenced voltage and current signals in pertinent reference frames.

Part (v) Show that the equilibria of the dynamics of the GFM inverter with droop control are obtained from the solution of the following nonlinear equations:

Lf Lf

√

R

− f iq,eq − ωiid,eq + 2(E sinδeq) = 0,

Lf Lf (8d)

ωnom , (8a) , (8b)

(8c)

, (8e)

where δeq,Veq are the terminal voltage amplitude and phase-angle equilibria corresponding to the voltage and phase dynamics; id,eq,iq,eq are the equilibrium values of the d and q axis current dynamics;

and Peq is the equilibrium value of the filtered active power.

Part (vi) We will now derive a small-signal model for the dynamical model. The state vector of

the small-signal model is defined as ∆x = [∆δ,∆V,∆id,∆iq,∆P]&gt;. The dynamics of the small-signal model are obtained by linearizing the dynamical model you derived in Part (iv). The small-signal model is compactly represented as ∆˙x = A∆x, where A is the Jacobian matrix of the nonlinear dynamical model evaluated for the equilibria referenced above. Write out the A matrix (25 entries) for this small-signal model.

Figure 2: Voltage source inverter with droop controller. The “power calculation” block calculates the active- and reactive-power using (7), the “low-pass filter” block comprises two low-pass filters with cutoff frequency of ωc, the “droop control” block denotes the droop relationships given in (3), and the “voltage generator” block generates the PWM modulation signals in the αβ reference frame given corresponding polar-coordinate inputs.

Problem 4. Consider the half-bridge circuit with current control illustrated in Fig. 3. Suppose we employ the following PI compensator:

. (9)

Part (i) With appropriate feed-forward cancellation, show that you obtain the circuit in Fig. 4 in a local dq reference frame.

Part (ii) Show that the closed-loop response from the d and q-axis current references to currents are given by

. (10)

Part (iii) Prove that the closed-loop transfer function, H(s), is first-order with time constant, τ,

, (11)

if and only if the time constant τc of the PI compensator, τc = k kpi , matches the time constant τf of the inductive output filter τf = RL.

Figure 3: Voltage source half-bridge circuit with output RL filter.

Figure 4: Voltage source half-bridge circuit with output RL filter in dq reference frame with feedforward cancellation.
