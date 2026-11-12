# Explainable-Credit-Risk

## The problem

## The problem

Every decision made with the help of AI deserves an explanation. Banks increasingly
use AI to support decisions about who receives a loan, and these decisions affect
people's lives. Customers and regulators have a right to know why a loan was
approved or rejected.

But an explanation can sound convincing and still be wrong. When an AI system
explains a decision in plain language, it might mention reasons the model never
used, or miss the reasons that really mattered. This is called an unfaithful
explanation. An AI might also be sycophantic: changing its explanation simply to
agree with what a person wants to hear. Is the explanation truly correct, or only
correct for now? Does it last? How accurate is it? And what could go wrong if it
isn't? With AI, anything can happen, so we should know before it does.

This project measures and tests whether AI-generated explanations of credit
decisions are faithful to what the model actually did, so that banks can trust
them and people are not misled about decisions that affect them.


## The question
Can banks trust AI-generated explanations of credit decisions?

## The plan
1. Build and understand a credit risk model (German Credit dataset)
2. Move to realistic data and rigorous explanations (SHAP)
3. Evaluate whether AI-generated explanations are faithful/accurate to the model

## Status
🚧 Work in progress: currently exploring the data (Step 1)