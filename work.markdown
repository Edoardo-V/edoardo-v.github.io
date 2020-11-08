---
layout: default
title: Work
permalink: /work/
---

I work in Intesa Sanpaolo, an italian bank based in Milan. I'm in the XVA Management desk which prices and hedges the x value adjustments. 

<img src="/images/screen.png" alt="drawing" width="600"/>

(OTC) derivatives are highly customizable 
derivative contracts that are privately negotiated
between two counterparties outside of an exchange. 
For their flexibility, they are used by a
variety of market participants to manage their exposure to the underlying financial risk. 

OTC derivatives mostly represent contingent claims
that entail bilateral payment obligations; 
examples include interest rate swaps or cross-currency swaps. 
Non-performance (credit) risk associated with these payment 
obligations is normally negligible, as it is substantially mitigated 
by the frequent exchange of collateral margin security between the two parties;
this is especially true for OTC derivatives traded between
regulated financial institutions, 
where such credit support practices are normally mandatory.
For this reason, OTC derivatives in the interdealer market
are usually priced as if they were counterparty ``risk-free''.

However, when dealing with non-financial clients, banks
may trade without collateral margin security.
Dealing on uncollateralized lines is required for instance 
by most corporate treasurers, due to the costs and
sophistication required to set up and run collateral exchange operations.
The lack of collateral security exposes banks to potential credit risk associated with 
the impossibility of fully recovering unrealised profits 
in case of a default of the corporate client.

Such risk is often hybrid in nature, as it depends on both the underlying
risk drivers for the contingent claim and on counterparty default event risk.
From the 1990s, dealers have started adjusting the price of uncollateralized OTC derivatives to
take into account counterparty risk, by adding 
a (negative) term called Credit Value Adjustment (CVA) to the
``risk-free'' value of the derivative.

Hence, CVA gradually became a generally accepted practice in the manufacturing reality
of derivative products, to the extent that it was subsequently recognized as 
a component of the fair value\footnote{Fair value is defined by International
Financial Reporting Standard (IFRS) 13 as ``the price that would be received to sell 
an asset or paid to transfer a liability in an orderly transaction between 
market participants at the measurement date (i.e., an exit price)".} 
of derivatives both in international
accounting standards and by prudential capital regulators.

In the rest of this section we describe a widely used approach to model CVA. However, first of all one should note two characteristic elements of counterparty credit risk: the first is its bilateral nature, which will be discussed further in the next section.
The fact that either party to the contract may default creates symmetric perspectives with respect to an assessment of the
price of risk associated with the transaction.
In the following we take the point of view of a financial institution $I$
(a bank), while the counterparty $C$
will be one of its clients.

The second element to be considered is 
that, differently from traditional credit risk, the notional 
amount of the exposure is uncertain, as it is given at the time of default by the
current market value of the derivative, which in turn is contingent on 
the underlying risk factors.
Here we need to take into account how the exposure---the amount at risk---is formed:
based on the standard contractual framework, when a party defaults, the 
derivative is ''closed-out'', i.e. it is immediately terminated and replaced with
a claim that one party owes to the other for a fixed amount (the
''close-out amount'') equal to the net
current value of the derivative at the time of default.
Due to the bilateral nature of the derivative, 
the close-out amount can be owed by either party, with different 
implications in terms of credit risk for the bank.

At default, the close-out amount is determined by the remaining party 
(i.e.\ the non-defaulting one) by estimating the cost of 
replacing the contract with an identical one with a new counterparty.
The replacement cost (also called the Mark-to-Market, or MtM) is
conventionally assumed to be measured in the interdealer market on collateralized lines,
therefore MtM is estimated as if it were counterparty ''risk-free'', i.e.\ without
consideration for any counterparty value adjustment terms.
We can now introduce the notion of \textit{Credit Exposure} (CE),
which represents the close-out amount from the point of view of the bank.
As anticipated, the effect of the client's default is different depending 
on the sign of MtM at the time of default:

 + if the Mark-to-Market value is positive, then the (defaulted) client owes the close-out
    amount to the bank; the bank may expect to recover this amount only partially
    via insolvency proceedings upon liquidation of the client's assets.
 + if the Mark-to-Market value is negative, then the bank owes the balance to the client;
    the bank has not defaulted, so it can fully honour this obligation.

Mathematically, CE can be expressed by:
$$
\begin{align}\label{eq:CE}
    CE(\tau_C)=\max[MtM_{\tau_C}, 0],
\end{align}
$$
where, at time $$t$$, an OTC derivative with maturity $T$ is considered and $$\tau_C\in(t,T)$$ is the default time of the counterparty $C$. 
A related quantity is the \textit{Expected Exposure} (EE) at time $t^*\in(t,T)$
\begin{align}
    EE(t^*)=\mathbb{E}_t[MtM_{t^*}|MtM_{t^*}>0].
\end{align}

As discussed, experienced loss upon default is only part of $CE$, as the bank may 
expect to recover part of the close-out claim amount in the insolvency proceedings.
The recovered fraction of $CE$ is estimated by the recovery rate $R_C\in[0,1]$ of the client.
Correspondingly, the lost fraction is the Loss Given Default $LGD_C=1-R_C$.