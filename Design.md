# Project Bank

This document describes the architecture and implementation considerations for project __Bank__.

## 1. Scope

> What is the project about?

- Project goal and purpose
- End deliverables, end conditions (when are we done?)
- critical success factors (-> helps to prioritize user stories)

- what is the project NOT about, what are the boundaries?

### Functional Requirements

> list all known requirements here.
> if you find any contradictions, make a note and clarify with the customer.
> if there are unclear requirements, you can make assumptions, but you have to clarify with the customer. Add them to the paragraph below.

### Quality Requirements
>
>

### Infrastructure

> what is the environment? Here you mention anything you cannot change or choose when doing the project implementation.

### Assumptions

> if during requirement analysis there are made assumptions, write them down and evaluate asap with the customer.

### Terms and Definitions

> since language is a very incorrect means of describing thoughts, use this section to clarify what you mean when e.g., talking of "People", "Customer", ...
> Ideally, use the terms and the description of the domain model. If you do not know a term (or you are not sure -> assumption), ask and then write it down together with explanation.

## 2. User Model

### User Roles

> What are the key users? How do they differ?

- clerk
- customer

### Domain Use Cases / User Stories

#### UC1: The system must allow to create a new bank account.

As a __costumer__ I want to __create a account__ so that __zzz__.

__Preconditions:__

> are there any?

__Acceptance 1:__

> good case
> add more as needed

__Acceptance 2:__

> what happens on error?
> add more as needed

__Remarks:__

> anything else we should think of when implementing that?
> any dependencies?

#### UC2: Title

As a __xxx__ I want to __yyy__ so that __zzz__.

__Preconditions:__

> are there any?

__Acceptance 1:__

> good case
> add more as needed

__Acceptance 2:__

> what happens on error?
> add more as needed

__Remarks:__

> anything else we should think of when implementing that?
> any dependencies?

#### UC3: Title

As a __xxx__ I want to __yyy__ so that __zzz__.

__Preconditions:__

> are there any?

__Acceptance 1:__

> good case
> add more as needed

__Acceptance 2:__

> what happens on error?
> add more as needed

__Remarks:__

> anything else we should think of when implementing that?
> any dependencies?


### User Interface

> A short description of the UI - in our case the CLI

## Domain Model

### Data Structures

> Which data do we have to process (from the Domain Model)? How is it structured in the Domain Model?

### Information Flow

> Which Data goes where? Who drives data exchange?

### Configuration Data

> do we have any? if yes, describe.

### Domain specific Error Handling

> is there any? if yes, describe.

## 3. Architecture Model
 
This chapter describes the architecture model of project __XXX__.

### Key design decisions

These decisions drive the architecture. If we need to change these, there should be a good reason!

__KDD 1:__ The implementation language is C (or C++).

__KDD 2:__ ...

> add more as needed

### System Context

> Is there anything we have to interact with?

### Static Architecture

> which data objects, which components/modules
> do a UML diagram here
> then describe each data obect and module in a separate paragraph below

#### _Module1_

#### _Module2_

...

### Configuration

> if any, describe here how it is done
> if there are startup parameters in the CLI, describe them here

### Dynamic Architecture

#### Startup

#### Shutdown

#### ... at least one sequence for each UC/Acceptance criterium above ...

## 4. Operational Qualities

### Performance

### Availability

## 5. Testability

> describe integration tests, if any
> describe system tests, if any

## 6. User Manual

> if needed, present a typical workflow here
> this can already be described in the system tests above, though

## 7. Open issues

> if during design or implementation any issue is found, make an entry here
> at the end there might be a list of issues, but all of them shall no longer be open but rather solved or clarified.