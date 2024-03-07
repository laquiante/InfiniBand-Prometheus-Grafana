Keywords:

InfiniBand
IB
Prometheus
Grafana
Ubnutu
ConnectX


Demo to show how all InfiniBand Counters of the whole fabric can be imported into Prometheus and visualized via Grafana.

My lab data source: Dell XPS-15 | 22.04 LTS | In-Box OFED | Mellanox ConnectX-5

![grafik](https://github.com/laquiante/InfiniBand-Prometheus-Grafana/assets/33266194/97523051-42a9-4d29-94e8-91feb6642b0e)

Simple flow of information:
![grafik](https://github.com/laquiante/InfiniBand-Prometheus-Grafana/assets/33266194/c9fa8b7d-9c23-45db-ae9a-75a060fee82e)

Setup external monitoring:
(works for both Ethernet (e.g. EVPN/EVPN-MLAG/EVPN-MH) and InfiniBand (e.g. FTREE))
![grafik](https://github.com/laquiante/InfiniBand-Prometheus-Grafana/assets/33266194/3d52b495-196e-452f-a718-297da0d308f6)

