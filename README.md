# chart-kured
Helm Chart for Weaveworks Kured

## Links
* https://github.com/weaveworks/kured

## Configuration
The following table lists the configurable parameters of the Kured chart and their default values.

| Parameter                  | Description                                               | Default                                            |
| -------------------------- | --------------------------------------------------------- | ---------------------------------------------------|
| `image`                    | Full image url                                            | `quay.io/weaveworks/kured:support-k8s-1.10-5731b98 |
| `slackWebhookUrl`          | slack hook URL for reboot notfications                    | `nil`                                              |
| `slackUsername`            | slack username for reboot notfications                    | `kured`                                            |
| `serviceAccount`           | Service account for RBAC                                  | `kured`                                            |
