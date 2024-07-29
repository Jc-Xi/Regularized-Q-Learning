# Regularized-Q-Learning
Regularized Q Learning with Linear Function Approximation

## GridWorld: Convergence result
<img width="773" alt="Convergence_plot" src="https://github.com/user-attachments/assets/a7a1a774-ec25-44dd-8e62-64999fb7ba01">

## GridWorld: Fixed Point
![FixedPoint](https://github.com/user-attachments/assets/7a52e08e-1d0c-42f1-9f3d-3276220be5a0)

## MountainCar Result
|  d  |            Q-learning            |                  Target\& Truncation                 |         CQL        |            Double QL            |    Regularized Q-Learning, $\tau = 0.01$    |     Regularized Q-Learning, $\tau = 0.05$    |
|:---:|:--------------------------------:|:-------------------------------------:|:------------------:|:-------------------------------:|:-------------------------------:|:-------------------------------:|
|  30 |        $-177.28 \pm 32.00$       |          $-159.76 \pm 34.20$          | $-199.37\pm 06.27$ |        $-177.51\pm 33.73$       | $\boldsymbol{-144.36\pm 26.46}$ |        $-177.83\pm 30.09$       |
|  60 |        $-143.08 \pm 32.47$       |          $-148.40 \pm 27.74$          | $-200.00\pm 00.00$ |        $-132.76\pm 31.54$       | $\boldsymbol{-121.01\pm 31.82}$ |        $-123.84\pm 28.35$       |
|  90 |        $-175.40 \pm 17.77$       |          $-161.35 \pm 20.99$          | $-200.00\pm 00.00$ |        $-146.78\pm 22.74$       |        $-121.37\pm 19.84$       | $\boldsymbol{-120.31\pm 19.20}$ |
| 120 | $\boldsymbol{-138.74 \pm 11.00}$ |          $-140.92 \pm 12.47$          | $-199.12\pm 03.97$ |        $-146.23\pm 12.77$       |        $-176.17\pm 22.65$       |        $-145.15\pm 29.48$       |
| 150 |        $-141.04 \pm 24.77$       |          $-140.46 \pm 26.30$          | $-200.00\pm 00.00$ |        $-155.60\pm 19.43$       |        $-139.58\pm 20.59$       | $\boldsymbol{-120.17\pm 20.64}$ |
| 180 |        $-135.62 \pm 32.01$       |          $-134.34 \pm 32.05$          | $-196.32\pm 13.61$ | $\boldsymbol{-110.66\pm 20.87}$ |        $-120.88\pm 22.50$       |        $-122.64\pm 22.01$       |

## Smooth Truncation V.S. Hard Truncation
![屏幕截图 2024-01-14 212333](https://github.com/user-attachments/assets/7466317a-7ec1-4e73-bc8a-17a89a57bb72)

## Bias Introduced by Smooth Truncation
<img width="896" alt="Bias" src="https://github.com/user-attachments/assets/6df000ba-3ad5-44d2-9bad-c6b68be43d19">
