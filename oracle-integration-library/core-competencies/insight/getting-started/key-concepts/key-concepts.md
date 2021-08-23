# Oracle Integration Insight Key Concepts

## About this Lab

The Lab will cover Orcale Integration Insight key concepts and terminology for each stage of building, activating, mapping a model and Console. 

Estimated Lab Time: This Lab will be 10 minutes.

## MODEL
A model is a business process, comprising of Milestone(s), a Unique Instance Indentifier and Alert(s). A model passes through several states during its lifecycle. There are 8 states: 
* Draft: A newly created model is in this state until the model is activated. In this state, changes can be made to the model and no metrics are collected. A draft model can be exported to later be imported into another Insight instance.
* Configured: A model moves into this state when its milestones, indicators, and unique instance identifier have been defined and milestones have been mapped to a business process. A model in this state is ready to activate.
* Activation In Progress: A model is in this state when activation has been initiated.
* Timeout: A model falls into this state when it times out after attempting to activate for five minutes.
* Activated: When a model is in this state, metrics are being collected, and changes are not possible. An activated model can be exported to later be imported into another Insight instance.
* Deactivated: A model moves into this state when you specifically deactivate it.
* Failed: A model falls into this state when it encounters issues during activation.
* Unknown: A model may move into this state when the state of the model cannot be determined as activated or deactivated. You can perform all lifecycle actions on a model in an unknown state.

## Milestone
A milestone is a key component of an Insight Model. Milestone(s) define points in a business process that represent progress and map to at least one activity in the business process implementation. A milestone requires an Initial and a Terminal. 
There are 5 types of Milestones, which are Initial, Standard, Error, Terminal and Terminal/Error. Every milestone requires an initial and a terminal


