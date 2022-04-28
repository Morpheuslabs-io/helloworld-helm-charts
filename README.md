## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add ml-helloworld https://Morpheuslabs-io.github.io/helloworld-helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
ml-helloworld` to see the charts.

To install the helloworld-helm-charts chart:

    helm install my-helloworld-helm-charts ml-helloworld/helloworld-helm-charts

To uninstall the chart:

    helm delete my-helloworld-helm-charts
