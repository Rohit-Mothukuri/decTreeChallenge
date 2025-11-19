# Answer Review - Decision Tree Challenge

## ✅ **Question 1: Numerical vs Categorical Encoding**

**What the question asks:**
- How should zip code be modeled, numerically or categorically?
- Is zip code ordinal or non-ordinal?

**Your answer:**
- ✓ Correctly states zip code should be categorical
- ✓ Correctly identifies it as non-ordinal
- ✓ Explains why categorical encoding is needed
- ⚠️ Uses generic "around 0.00%" instead of actual calculated values from your code

**Suggestions:**
- Your code calculates `zipcode_importance` (numerical) and `zipcode_percent` (categorical aggregated)
- Consider adding a small code chunk that displays these actual values to make the answer more specific to your outputs
- Otherwise, the answer appropriately addresses the question

---

## ✅ **Question 2: R vs Python Implementation Differences**

**What the question asks:**
- Why do output trees and feature importance differ between R and Python?
- What does R offer that Python does not?
- Which language does better job?
- Quote from scikit-learn documentation about weakness

**Your answer:**
- ✓ Explains fundamental difference (native categorical support vs one-hot encoding)
- ✓ Lists what R offers that Python doesn't
- ✓ Includes the required scikit-learn documentation quote
- ✓ States which language is better with reasoning
- ✓ References actual code output ("25+ binary features")

**Status:** **APPROPRIATE** - Fully addresses all parts of the question with documentation support

---

## ✅ **Question 3: Better Categorical Handling in Python**

**What the question asks:**
- Suggestions for implementing decision trees in Python with proper categorical handling (not one-hot encoding)
- Provide link to source and quote from source

**Your answer:**
- ✓ Provides three concrete options (HistGradientBoosting, CatBoost, LightGBM)
- ✓ Includes documentation quotes with links for all three
- ✓ Explains how each works differently from one-hot encoding

**Status:** **APPROPRIATE** - Meets all requirements with multiple options and proper citations

---

## Summary

All three answers are **appropriate and address the questions**. The only minor improvement would be to reference actual calculated values from your code outputs for Question 1, but using "around 0.00%" is acceptable for the narrative style you're using.

