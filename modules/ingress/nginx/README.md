
# Annotation

This repository contains the NGINX controller built around the Kubernetes Ingress resource that uses ConfigMap to store the NGINX configuration. Make Ingress-Nginx Work for you, and the Community from KubeCon Europe 2018 is a great video to get you started!!

Learn more about using Ingress on k8s.io
What is an Ingress Controller?

Configuring a webserver or loadbalancer is harder than it should be. Most webserver configuration files are very similar. There are some applications that have weird little quirks that tend to throw a wrench in things, but for the most part you can apply the same logic to them and achieve a desired result.

The Ingress resource embodies this idea, and an Ingress controller is meant to handle all the quirks associated with a specific "class" of Ingress.

An Ingress Controller is a daemon, deployed as a Kubernetes Pod, that watches the apiserver's /ingresses endpoint for updates to the Ingress resource. Its job is to satisfy requests for Ingresses.