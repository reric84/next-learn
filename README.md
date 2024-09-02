## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Install

- create k8s namespace: `kubectl create namespace next-learn`

- create config `kubectl config set-context next-learn --cluster=microk8s-cluster --user=admin --namespace=next-learn`

## Develop

```bash
skaffold dev
```

## Production

```bash
skaffold run -p production
```

## Login

- Email: `user@nextmail.com`
- Password: `123456`