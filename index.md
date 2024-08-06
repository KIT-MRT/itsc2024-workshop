---
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.5"
  overlay_image: assets/images/header_from_unsplash_dot_com.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
title: 'Interaction-driven Behavior Prediction and Planning for Autonomous Vehicles'
excerpt: 'An ITSC2024 workshop.'

organizers_row:
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/8Ih7coZPaAkRkId/download
    alt: "Sascha"
    person_name: "Sascha Hornauer"
    person_affiliation: "MINES Paris"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/QdPGyNJqiVWReXo/download
    alt: "Marcel"
    person_name: "Marcel Hallgarten"
    person_affiliation: "University of Tübingen / Bosch"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/uM0S69C2HvK1P0g/download
    alt: "Max"
    person_name: "Maximilian Naumann"
    person_affiliation: "Bosch Center for Artificial Intelligence (BCAI)"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/xUp0YRt2gkYeCrW/download
    alt: "Eike"
    person_name: "Eike Rehder"
    person_affiliation: "Robert Bosch GmbH"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/EeNQ4Sd6Xvd3bpj/download
    alt: "Jiachen"
    person_name: "Jiachen Li"
    person_affiliation: "Stanford University"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/St0MsMoWj08Ui6K/download
    alt: "Wei"
    person_name: "Wei Zhan"
    person_affiliation: "University of California at Berkeley"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/nR8bFlVEe4QlsPp/download
    alt: "Martin"
    person_name: "Martin Lauer"
    person_affiliation: "Karlsruhe Institute of Technology (KIT)"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/QATKLUjJ1l2BA6F/download
    alt: "Masayoshi"
    person_name: "Masayoshi Tomizuka"
    person_affiliation: "University of California at Berkeley"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/EHn5azQzYNmRmM0/download
    alt: "Arnaud"
    person_name: "Arnaud de La Fortelle"
    person_affiliation: "Heex Technologies"
  - image_path: https://cloud.minesparis.psl.eu/index.php/s/F2fdqs7ZuidY5fW/download
    alt: "Christoph"
    person_name: "Christoph Stiller"
    person_affiliation: "Karlsruhe Institute of Technology (KIT)"

schedule:
  - time: "8:30 - 8:40"
    event: "Organizers"
    content: "Introduction"
  - time: "8:40 - 10:00"
    event: "TBA"
    content: "Regular Talks 1-4"
  - time: "10:00 - 10:30"
    break: "Coffee Break"
  - time: "10:30 - 11:30"
    event: "TBA"
    content: "Regular Talks 5-7"
  - time: "11:30 - 11:50"
    event: "TBA"
    content: "Keynote"
  - time: "11:50 - 12:00"
    event: "Organizers"
    content: "Conclusion"
---

This workshop will be held at the [27th IEEE International Conference on Intelligent Transportation Systems (ITSC)](https://ieee-itsc.org/2024/), on September 24 - 27, 2024
Edmonton, Canada 

## Topics
The topics of interest of the workshop include, but are not limited to:

- Cooperative and comprehensible motion planning 
- Probabilistic decision making and motion planning (including MDPs, POMDPs, MMDPs) 
- Probabilistic behavior prediction (with help of semantic high-definition maps) 
- Second-order effects in heavy interactive scenarios
- Evaluation and benchmarking of the aforementioned topics


Please check the official program for potential updates: [https://ieee-itsc.org/2024/program/](https://ieee-itsc.org/2024/program/)

## Workshop Content

Research on Automated Vehicles has experienced vast progress over the last decades. Today, first prototypes are sufficiently safe to drive on selected roads in public traffic. Nevertheless, safety comes at the price of overly conservative behavior, leading to inconvenient situations, for example, at unprotected left turns or merging scenarios. Presumably, the main reasons for this behavior include (a) errors in the prediction of other traffic participants, especially in interactive scenarios and (b) the lack of probabilistic considerations in motion planning. 


**Comfortable Automated Driving**: While safety should never be put at risk, worst case behavior of others should not be the default for the motion plan of an automated vehicle. Rather, with a safe reaction to such worst case behavior always in reserve the intended trajectory should be comfortable, less conservative and thereby potentially closer to human expectations. Proposal and exchange of these kind of approaches is the first aim of the workshop. 


**Multimodal Behavior Prediction**: For such behavior, sophisticated behavior prediction approaches for other traffic participants are necessary, going beyond constant velocity assumptions. Predictions must be probabilistic and allow for maneuver options for other vehicles. Often, there is not “the right prediction”, but many. The choice is influenced by destinations as much as individual driving behaviors and potentially even the drivers’ mood. Thus, a simple evaluation against a ground truth is not possible. Prediction approaches, including but not limited to machine learning based approaches, as well as proposals for their evaluation, are the second main goal of this workshop.


**Comprehensible Automated Driving**: For motion planning in highly interactive scenarios alike, a “ground truth” or “best option” may not exist. To be comprehensible and predictable for other road users, a good plan should be a subset of an expected prediction for a vehicle in the same situation. The combination of planning and prediction, including but not limited to their evaluation and benchmarking, is the third aim of the proposed workshop.


**Effects of Automation on Traffic**: Data-driven predictions can end up being implicitly conditioned on second-order effects. For example, seeing a recording vehicle or no driver in an autonomous car can influence traffic participant’s decisions. Fixed settings in automated functions, such as safe distances, can influence the traffic flow on highways. While this can potentially introduce a distribution shift for prediction algorithms it could be also leveraged to purposefully shape traffic. We invite therefore also approaches investigating these second-order effects, propagating in highly interactive scenarios.

## Preliminary Agenda
{% include schedule %}

## Organizers
{% include feature_row id="organizers_row" %}


Please get in touch with  [sascha.hornauer@mines-paristech.fr](sascha.hornauer@mines-paristech.fr) or any of the organizers in case you have any further questions.

## Past Editions

At IV2024, the organizers hosted the latest edition of this workshop: [https://kit-mrt.github.io/iv2024-workshop/](https://kit-mrt.github.io/iv2024-workshop/).
