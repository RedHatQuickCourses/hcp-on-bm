# About this Training

**Click here: [![Contribute](https://www.eclipse.org/che/contribute.svg)](https://devspaces.apps.tools-na100.dev.ole.redhat.com/#https://github.com/RedHatQuickCourses/hcp-on-bm) to start the development using devspace.**

# Objectives

This training provides a comprehensive guide to deploying OpenShift Hosted Control Planes (HCP) on a single bare-metal host, leveraging KVM for virtualization.

You will learn how to set up a proof of concept environment to explore HCP capabilities, with help of provided Ansible playbooks.


# Source materials

Course contents are adapted from a [google docs](https://docs.google.com/document/d/1V_Yc65pFyubHEcPx11IhmH6fPazsBxZOBfUKpj4p8lA/edit?tab=t.0#heading=h.d27s564v3u2o) write out of the lab steps, and a [video recording](file:///home/flozano/Downloads/hcp-on-bm/OTG17A-Maximizing%20ROI%20with%20Virtualized%20Control%20Planes_%20Strategies%20for%20Scalable%20Environments.mp4) of the presentation during RH1 2025 by Ami Desai, Praveen Thakur, and Sadique Puthen. The write out detailed the preparation of the lab environment, while the recording detaild actual provisioning of HCP clusters.

The google doc was exported into HTML files, so it was possible to extract individual screenshot files, and converted to asciidoc, together with content from the presentation slides and speaker notes.

Figures required small changes from the [original RH1 presentation deck](https://docs.google.com/presentation/d/1zGBVl1AV_-GNG-UVec-VNMkxQ7uVVydXR0ugEhknk0E/edit?slide=id.g3340822569d_0_3#slide=id.g3340822569d_0_3) to remove the slide background, and are [here](https://docs.google.com/presentation/d/1wEqwLJ9sRIyFo06fdHCB3KIYs_SunoIu-zcfq1xmdRo/edit?slide=id.g362d151231b_0_158#slide=id.g362d151231b_0_158) and exported from google slides to either SVG (preferred) or to PNG files, which are included in this repository.

NOTE: the source materials are available only to Red Hat employees.

The playbooks required to configure the bare metal node, helper VMs, and deploy the hub cluster, are [forked](https://github.com/RedHatQuickCourses/hcp-on-bm-playbooks) to ensure reproducibility of this course labs and allow for evolution of the original content.

The introduction used a bit of AI to generate a summary of course objectives, topics, and prerequisites -- all properly reviewed and tweaked by a human.