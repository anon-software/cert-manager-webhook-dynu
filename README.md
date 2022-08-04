## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add cert-manager-webhook-dynu https://dopingus.github.io/cert-manager-webhook-dynu

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
cert-manager-webhook-dynu` to see the charts.

To install the dynu-webhook chart:

    helm install dynu-webhook cert-manager-webhook-dynu/dynu-webhook

To uninstall the chart:

    helm delete dynu-webhook
