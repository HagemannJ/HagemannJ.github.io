---
layout: post
title: "An analysis of TinyJAMBU"
date: 2021-10-28
---

My final year project was completed under the supervision of Dr. Leonie Simpson with a team of four students. The project involved the analysis of the lightweight symmetric encryption algorithm "TinyJAMBU". The project was completed over the course of 2021 and was an absolute pleasure to undertake. I gained great insight into a range of cryptanalytic techniques and technical, low-level coding skills. Below is the abstract for our research. If you would like to read the full paper, please send me an <a href="mailto:jhagemann52@gmail.com">email</a>.

<H4>Abstract</H4>
<i>TinyJAMBU is a proposed lightweight cryptographic algorithm that was created in response
to the open call competition held by the National Institute of Standards and Technology. In this
paper, we investigate the stated security of the algorithm using several common cryptographic
analysis techniques. We outline the methodology along with our findings throughout the project.
In the statistical analysis we perform various randomness tests, finding that the algorithm appears
sufficiently random. In investigating the differentials of plaintext and ciphertext produced by the
algorithm, no apparent properties are exhibited which we would disadvantageous. Attempts at
forgery were made against three separate areas: modification of the initialisation parameters,
modification of the associated data and plaintext, and modification of the state for MAC generation. The team then produced their own modified version of the algorithm, reducing the state size
from 128-bits to 32-bits. Using the modified cipher the team measures the theoretical collision
rate against a practical implementation. Results from practical experiment matches the expected
theoretical probability of collisions.
</i>
