# Lightning Routing

## Reading

| Content                                                                                       | Time  | Tags                    |
|-----------------------------------------------------------------------------------------------|-------|-------------------------|
[Network topology creation & maintenance](https://diyhpl.us/wiki/transcripts/scalingbitcoin/tel-aviv-2019/edgedevplusplus/lightning-network-topology/) | 20 min | routing |
[Routing problems and solutions (rendezvous, trampoline)](https://www.youtube.com/watch?v=1O-bhcbh9vE) | 22 min | rendezvous, trampoline, video |
[Amount-independent payment routing in Lightning Networks](https://medium.com/coinmonks/amount-independent-payment-routing-in-lightning-networks-6409201ff5ed) | 6 min | routing |
[Multi-path payments (MPP)](https://youtu.be/Og4TGERPZMY) | 21 min | AMP, video |
Rendezvous routing ([presentation](https://youtu.be/Ms2WwRzBdkM) or [wiki write-up](https://github.com/lightningnetwork/lightning-rfc/wiki/Rendez-vous-mechanism-on-top-of-Sphinx)) | 10 min | rendezvous, routing |
[Gossip Protocol/Path Finding](https://youtu.be/MeEFUaRnMak) | 56 min | gossip protocol, video |
[Onion Routing](https://youtu.be/toarjBSPFqI) | 11 min | onion routing, video |
[Onion Routing - deep dive](https://youtu.be/D4kX0gR-H0Y) | 38 min | onion routing, video |
[Sphinx](https://github.com/t-bast/lightning-docs/blob/master/sphinx.md) | 20 min | sphinx, _optional_ |

## Discussion Questions

1. On the base layer, the quality of the nodes you connect to is largely irrelevant provided they are an honest peer. How does this differ in Lightning when opening a channel to a peer?

### Network topology creation & maintenance

1. What practical measures can nodes wishing to route on Lightning take to improve their success? Does this cause issues for new entrants?

### Multiple Path Payments

1. What is the difference between MPP and AMP payment splitting?

### Trampoline Payments

1. Can trampoline payments be combined with atomic multi-path payments to mitigate privacy issues?

### Rendezvous Routing

1. Explain rendezvous routing in plain English.
1. Would it make sense to chain multiple rendezvous meeting points?

### Watchtowers

1. How do watchtowers work with non-advertised channels when part of the graph is not known? Or with trampoline when the routing calculation is outsourced?
