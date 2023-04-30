---
layout: page
title: Dynamic Network Inventory
description: Using Ansible for documenting network devices on Netbox.
img: assets/img/Ansible_logo.png
importance: 2
category: work
---

I developed this for a company I worked for the goal was to dynamically/automatically inventory network devices. These devices were primarily Cisco products. I created Ansible playbooks to gather device information and then upload the information into Netbox. Once devices are in Netbox, I worked on a playbook that periodically checks device information using the device configuration.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/netbox.png" title="Netbox Logo" class="img-fluid rounded z-depth-1" %}
    </div>
</div>