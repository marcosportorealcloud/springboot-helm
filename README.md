## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add mvp-helm-springboot https://marcosportorealcloud.github.io/springboot-helm

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the mvp-helm-springboot chart:

    helm install my-springboot-helm mvp-helm-springboot/springboot-helm

To uninstall the chart:

    helm delete my-<chart-name>
