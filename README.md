# SurrealDB Social November 2023

![slide](https://github.com/rytswd/surrealdb-social-2023/assets/23435099/ffc6ad5e-bbf5-46e9-9218-6a93f5bc82b9)

> Date: 29th November, 2023
>
> Title: **Deploy SurrealDB to Kubernetes With GitOps**
>
> Presented by [@rytswd](https://github.com/rytswd)

Official Website:
https://www.eventbrite.co.uk/e/surrealdb-social-building-a-saas-deploying-surrealdb-to-kubernetes-tickets-750714265577

Recording: https://www.youtube.com/watch?v=04opYXTt3sc

Slide: https://dub.sh/surrealdb-social-nov-2023-gitops

## 🌄 About This Repository

This repository holds the supplementary materials for my talk at SurrealDB
Social Meetup, November 2023.

- Demo Steps and Details
- References

## 🛝 About Demo

You can find all the details in [demo.org](demo.org) file.

### Prerequisites

In order to run through the demo steps, you will need the following tools:

- `kubectl`
- `kustomize`
- `helm`

If you are to use KinD clusters instead of Civo, you will need `kind` as well.
Also, please note that having 3 KinD clusters will require some significant
compute resource on your machine.

### Tools Used

While you may not need all of the tools, the original demo used the following
tools:

- `kubectl`
- `kustomize`
- `helm`
- `k9s`
- `surreal`
- `mirrord`
- `kubectx`
- `civo` (from Civo)

On top of that, there were several completely supplementary tools used:

- Alacritty
- Arc Browser
- Emacs
- Nix

### Clean Up

When using Civo clusters, it is as simple as shutting them from the Civo console, or CLI. You should also remove the associated volumes which were associated with the cluster.

### Troubleshooting

If you found any misbehaviour with the setup, please feel free to create an issue. While I'm not intending to maintain with the latest details here, I still check activities and may be able to help.

## 🔎 References

https://civo.com
