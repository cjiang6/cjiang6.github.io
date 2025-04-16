---
title: "Preference Augmented Q-Learning for Patient Exercise Scheduling in a Robotic Rehabilitation Gym"
collection: publications
category: conferences
#permalink: /publication/2024-02-17-paper-title-number-4
#excerpt: 'This paper is about fixing template issue #693.'
#date: 2025-02-17
venue: '2025 IEEE International Conference on Rehabilitation Robotics (ICORR)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'V.R. Bharadwaj, B.A. Miller, V.D. Novak and C. Jiang, &quot;Preference Augmented Q-Learning for Patient Exercise Scheduling in a Robotic Rehabilitation Gym.&quot; <i>2025 IEEE International Conference on Rehabilitation Robotics (ICORR)</i>. accepted.'
---

**Abstract:** Robotic rehabilitation gyms enable groups of patients
to perform motor rehabilitation under the guidance of a
single therapist. While software can help process and present
patient exercise information in an easy-to-understand manner,
certain characteristics like motivation and fatigue are harder to
quantify using sensors. Human therapists are able to observe
these characteristics without precise sensor measurements and
use them to make intelligent patient-robot assignment decisions.
However, actively observing every patient in the group and
changing which robot they exercise with would distract the
therapist from delivering effective therapy. To help with this, we
propose a Preference Augmented Q-Learning assignment scheduler
that learns to create patient-robot assignment schedules for
group rehabilitation. The scheduler is trained to leverage expert
assignment preferences and implicitly incorporate motivation
and fatigue through expert guidance. The assignment scheduler
was tested using 1000 simulated patient groups with its results
compared against several baselines. Our assignment scheduler
outperformed all tested baselines, except for schedules created
by a simulated expert who had access to all the patients’
characteristics and could predict future exercise outcomes. In
simulation, the results show the effectiveness of incorporating
expert preferences into reinforcement learning models to improve
assignment scheduling without directly measuring hardto-
quantify factors.
