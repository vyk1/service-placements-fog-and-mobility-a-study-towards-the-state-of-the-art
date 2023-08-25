# Master's thesis

Service placements, fog and mobility: a study towards the state of the art

## Abstract

As most of the scenarios for positioning systems were outdoors and were historically
used for naval and warfare purposes, positioning systems were satellite-based. How-
ever, with the advent of the Internet of Things (IoT), these systems can be supported by
the TCP/IP protocol suite, which is able to accelerate their implementation in different
scenarios. By definition, the IoT can be described as a network of physical and hetero-
geneous objects connected to the Internet, and nowadays it is part of a wide range of
intelligent solutions, ranging from essential scenarios such as agriculture and power
grids to other solutions closer to end users, which can be smartphones, for example.
Because of their ubiquity, these devices, which can be referred to as edge devices,
contribute to the implementation of positioning systems in various contexts. These
applications integrate hardware and software to continuously provide the location of
devices. Indoor scenarios, such as hospitals and other buildings, because their spaces
are surrounded by concrete, require technologies and location methods different from
those used in outdoor scenarios, like GPS and other global navigation satellite systems.
Furthermore, certain contexts, such as museums and smart airports, may have dy-
namic variables, such as the number of discoverable devices, resulting in high network
latency for architectures based on Core Clouds. The growing development of IoT has
motivated the distribution of computational power to the edge of architectures, reducing
the request-response time and resulting in less processing in high-performance data
centers. Between the cloud and the users, there is the fog, a computing paradigm that
aims to scale computational resources closer to the users and enhance the quality of
service by reducing latency and increasing service awareness. However, as it brings
processing power closer to the edge of the network, it uses traditional service place-
ment strategies. Nevertheless, in dynamic mobile environments, a study evaluating the
system’s performance could benefit their performance and comprehend their particu-
larities (contextness) aside from fog node positioning and mobility models. This way,
the present work aimed to investigate if traditional location service placements could
be as space application agnostic in IPS (indoor positioning systems) as they are in
OPS (outdoor positioning systems), or even if they could be equivalent. To diversify the
study, experiments were made using adapted random mobility patterns supported by
simulations. Using the proposed methodologies and the simulation software iFogSim
v2, it was possible to explore clustered and edge-ward placements in both indoor and
outdoor positioning systems and develop a set of mobility models based on the equiv-
alence of the positionings. Our research showed the traditional placement strategies
are not equivalent to IPS, proving they are not comparable strategies and tend to have
worse performance for migration indoors. Also, it was determined that a lack of definition
of what constitutes indoor environments and context-awareness is an important factor
for IPS since the mobility models used tend to be randomized in the literature. Besides
the aforementioned findings and the standardized benchmarks developed, it was at-
tested that clustered placements tend to be closer to the space application agnosticism
promoted by the open source community

You can find the document [here](https://tede.ufsc.br/teses/PGCC1238-D.pdf).

## (Some) Products

- https://github.com/vyk1/cluster-formation-mobility-based-algorithm
- https://github.com/vyk1/cluster-experimentation-ops
