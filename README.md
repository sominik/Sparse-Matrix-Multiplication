# Sparse Matrix Multiplication: parallel computing
- This project implemented for  "Multi-core programming" course.
- The purpose of this Cuda project is learning parallel computing on GPUs.

## Observations
Our implementation of ACSR was run on the following GPU : <br/>

<img src="images\GPU_properties.jpg">

## Usage and Compilation
### Compliling and running ACSR
```
nvcc ACSR.cu -arch=sm_50
./a.out
```
(Enter the name of the dataset when prompted)

# Results

We tested this algorithm on several Sparse matrices with different dimensions and we will indicate the results further.

## Test 1:
**Dimensions of the matrix:**
- 130 * 130

**The number of non-zero values of this matrix:**
- 1282

**Output result:**

<img src="images\Test1_result.jpg">

---

## Test 2:
**Dimensions of the matrix:**
- 685 * 685

**The number of non-zero values of this matrix:**
- 1967

**Output result:**

<img src="images\Test2_result.jpg">

---

## Test 3:
**Dimensions of the matrix:**
- 1612 * 1612

**The number of non-zero values of this matrix:**
- 3718

**Output result:**

<img src="images\Test3_result.jpg">

---

## Test 4:
**Dimensions of the matrix:**
- 3079 * 3079

**The number of non-zero values of this matrix:**
- 53843

**Output result:**

<img src="images\Test4_result.jpg">

---

## Test 5:
**Dimensions of the matrix:**
- 10922 * 10922

**The number of non-zero values of this matrix:**
- 28922

**Output result:**

<img src="images\Test5_result.jpg">





