<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="../kubernetes-dashboard/screenshot-14-12-2024.png" width="400"/>
  <img src="../kubernetes-dashboard/screenshot-15-12-2024.png" width="400"/>
</div>

## Overview
High-level view of Kubernetes cluster - useful for monitoring, alerting and troubleshooting.

Works on local, bare-metal or cloud provided clusters (e.g. k3s, kind, minikube, Talos Linux, EKS etc..)

[https://grafana.com/grafana/dashboards/22523-kubernetes-dashboard/](https://grafana.com/grafana/dashboards/22523-eks-dashboard/)

<!-- https://github.com/adegoodyer/grafana-dashboards/kubernetes-dashboard -->

## Features
- network I/O
- k8s resource counts
- highlights pods not running
- CPU/RAM utilization (cluster, node, namespace and pod)
- CPU throttling information (namespace/pod)
- container restart information (namespace/pod)

## Dependencies
Last tested via `kube-prometheus-stack` Helm chart `v66.3.1`

However, will work when recent versions of the following Prometheus exporters are installed..
- `cAdvisor`
- `kube-state-metrics`
- `node-exporter`

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support
<a href="https://www.buymeacoffee.com/adegoodyer"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a book&emoji=📚&slug=adegoodyer&button_colour=5F7FFF&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00" /></a>

<!-- https://www.buymeacoffee.com/adegoodyer -->