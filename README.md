# Sofie automation AWS Infinidash
Library to enable the Sofie TV Automation system to have full vertical integration with the AWS Infinidash ecosystem. Bridging the gap between Infinidash orchestration and more traditional proven Node.js deployments.

This library is highly experimental. It currently contains (WIP):

* Blog about what has been discovered so far
* Terminology related to the DashCore
* Simple prototype application that has been used to use Infinidash hypervisor for self-governed Docker clusters
* Draft typescript interface

[New to Infinidash? This introduction tweet from Joe Nash is the best place to get started.](https://twitter.com/jna_sh/status/1410178986978775040)

## Abstract

## Concept: Infinite single sources of truth
In the hunt for the singlest source of truth, do we sacrifice scalability? What is the tradeoff of monotruth if it won't scale to meet real-world demands – and why do we have to choose in the first place?

We believe that the premise needs to be flipped. Instead of focusing on a single point of truth, let's start embracing multiple points of single truths. The difference is subtle but crucial. In a traditional monotruth paradigm you can only scale within the set keeping your state. Enabled by Infinidash's messaging component and reactiveness, we can now grow flops (aka. "Flop-farming") of truth in a well-stated manner. Plugging into ReactiStash, we can stack these vertically, for theoretically unlimited growth.

**Note:** Further investigation is needed before concluding on cost/benefit of scaling all state-handling in AWS. Pending ongoing tests done through the OpenDash initiative to conclude if there's viable open source alternatives coming in near future.

## Configurations
One of the hardest concepts for beginners to grasp regarding Infinidash is "Where does it run?". Strictly speaking, Infinidash does not simply "run" anywhere, it will be more accurate to say that it just "is", and it can "be" in a multitude of different contexts. But for simplicity, and targeting beginners in this readme, we will lay out some examples using legacy terms like "runs" and hope to make comparison with better known technologies easier this way. 

### Frontend

### Backend

### No-end

### Open-ended

## Disclaimer
This library is in no way associated with, or endorsed by, AWS nor the Infinidash trademark.
