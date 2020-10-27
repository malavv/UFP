# United Federation of Participants

The United Federation of Participants is an exploration of Federated Analysis in clinical epidemiology. One of the main concerns of epidemiology is to reach sufficient statistical power to make valid inferences. In practice, the effects of interest are often small or diluted by confounding, time or the use of proxy measures. These all increases the probability of making a type-II error (a false negative). The reason is that the smaller or more confounded the effect, the more likely it is to be confused with no effect. The solution is to gather more data, but as is often the case in clinical epidemiology, data is limited.

As clinical data is made of the records of clinical practice, it is bound to patients and often distributed throughout multiple indenpendant systems. It is often the case therefore that to gather more data, we have to either get the consent of more participants or get access and linked different systems. This is the difference between horizontally and vertically federated analysis. Either we get more samples (horizontal) or more features (vertical).<sup>1</sup>

For many reasons, pooling data is usually a challenge and can be impossible either practically or by design. But what if there was another way? What if we could access some of the "information" contained in this data without ever having access to the data itself? 

This is what federated analysis aims for. Scatter the analysis instead of pooling the data. This is akin to a Golang idiom or "Do not communicate by sharing, share by communicating". Let us divise way to keep the data where it is, and communicate the minimum amount of non-identifiable information possible to perform the analysis.

[1] Federated analyses, Technical, statistical, and human challenges (ppt).

## What's in here

In this repository will be an exploration of Federated Analysis applied to epidemilogy. Both practical and theoretical concerns will be explored and address with a focus on clinical epidemiology.

This repository will contain examples, and code related to my PhD work.

For additional context, you main look at https://github.com/malavv/UFP/wiki
