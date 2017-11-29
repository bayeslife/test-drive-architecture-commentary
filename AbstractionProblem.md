#  Test Driven Architecture : Abstraction Problem

One significant difference between test driven architecture and test driven development relates to the test and implementation life cycle.

In test driven development you can write a test and run it against the implementation.
By running the test one gets feedback on the test and the implementation which can be used to adjust either the test or the implementation.
This can occur repeatedly and rapidly.
Consequently there is a good feedback loop from the test to the implementation and vice versa.

When developing an architecture using a test driven approach it is not clear what the implementation is that tests should be written against.
Logically the 'implementation' should be fairly abstract concepts rather than realized system or implementation.

It would seem the implementation needs to be a model.

However we have to be careful that that model is representative of reality or we risk developing passing tests but being misled by the tests.

Its also the case that tests become much harder to write and validate as the model itself is being fleshed out and easily can become detailed to the point where the model moves away from being a model and becomes an implementation.

Possible the approach should be to develop tests against a set of established and 'known good' models.

So we would need to know how to
[establish models](./EstablishModels.md)
and
[how to write tests against established models](./TestAgainstModels.md)
and
[how replace the models with real implementation to validate the real implementation](./ReplaceModelsWithImplementation.md)
.

[back to Test Driven Architecture](./README.md)
