# 🔍 Fault Prediction Engine

## 📌 Overview

The Fault Prediction Engine determines possible faults based on processed system conditions.

## 🎯 Purpose

* Identify potential avionics faults
* Map system conditions to fault scenarios

## ⚙️ Functionality

* Combines multiple parameter conditions
* Uses predefined fault mapping tables
* Identifies affected subsystems

## 📥 Inputs

* Processed data from Logic Engine

## 📤 Outputs

* List of possible faults
* Subsystem identification
* Suggested faulty LRUs

## 🔗 Interaction

* Works with database fault mapping
* Sends results to Probability Engine

## ⚠️ Limitations

* Accuracy depends on rule definition
* Limited to predefined fault scenarios

---
