# su26-ai301-contribution
# Contribution [1]: Document pi_check correctly

**Contribution Number:** 1  
**Student:** Nithila 
**Issue:** https://github.com/Qiskit/qiskit/issues/10391  
**Status:** Phase I Complete

---

## Why I Chose This Issue

I chose this issue because it focuses on improving documentation for an internal function (pi_check) in Qiskit, which is important for understanding how the library works on handling numerical validation. Even though this function is no longer part of the public API, the discussion shows that developers still rely on it internally or encounter it during development and testing for future use and improve.

---

## Understanding the Issue

### Problem Description

The problem is that for the docstring for pi_check is inaccurate. Developers are unsure about what inputs it accepts, what outputs it produces, and under what conditions it returns True, False, or raises errors.

### Expected Behavior

The expexted behavior should clearly explain what pi_check actually does, including the inputs and the return values.


### Current Behavior

The current docstring does not clearly describe the function’s real behavior which often leads to confusion in undersatnding hte main program before delving into it's workings and can often also confuse a contributer's work.

### Affected Components

The affected components are the internal utility function pi_check and the documentation inside that needs reviewing.
