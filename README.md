# CVP Context Service Example

This project is a CVP Call Studio sample application that demonstrates a basic
Context Service use case of looking up a customer, creating a POD, and returning
the relevant customer information to ICM using the FromExtVXML variables.

This application is intended to be called from an ICM routing script, so a
sample ICM script has been included in the root directory. The sample ICM script
refers to a Precision Queue and Courtesy Callback ICM script - you can set these
to any relevant PQ and IVR queue script in your environment.
