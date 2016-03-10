# Famil.io Fork

## Steps to complete the task
1. Create fork of the https://github.com/Code-Mine-Development/Famil.io repository to your personal **GitHub** account (https://help.github.com/articles/fork-a-repo/)
2. Clone forked repository
3. Create branch `feature/WeddingLifeFact`

## Requirements
1. Use PSR-4 standard
2. Follow convention that is used across the project
3. Use PHP 7 features like return types etc.
4. Work **ONLY** on branch created in the previous steps!

## Task A
1. Create class `Famillio\Model\Person\Biography\Fact\LifeEvent\Wedding`
2. Create Interface `Famillio\Model\Person\Biography\Fact\MaritalStatusChangeFactInterface`
3. Interface `MaritalStatusChangeFactInterface` should have method for retrieving name of the person that is also involved in the event.
4. Class should extend `AbstractFact` class
5. Class should implement `MaritalStatusChangeFactInterface`
6. Class should be used to create objects that represent fact of the wedding - this requires implementation of all methods from Interfaces and `AbstractFact` class

## Task B
1. Create empty stubs for all classes that could represent LifeEvent and are in your opinion needed to fully represent someone’s biography.

## Task C
1. Push changes to branch created in your forked repository
2. Create pull request to main repository


## Technical info
- You can use internet and any sources that will help you
- You can include any composer library that can help you with the task
- Task should be completed within 60 minutes.
