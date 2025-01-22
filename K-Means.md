# K-Means

### Latihan Soal:
| customer | item bought | arrival frequency |
| -------- | ----------- | ----------------- |
| 1	       | 2           | 10                |
| 2        | 2           | 5                 |
| 3        | 8           | 4                 |
| 4        | 4           | 5                 |
| 5        | 5           | 7                 |
| 6        | 6           | 4                 |
| 7        | 1           | 2                 |
| 8        | 8           | 9                 |

- A department store in Jakarta area, would want to make sure that their sale campaigns are right on target. In order to do that, they have to cluster their customers based on total item bought and arrival frequency.
- You are asked to cluster the customer into 3 clusters (K = 3).
- The initial centroids / center are: (2, 10), (5, 8), and (1, 2)
- You must use Eucledian Formula for calculate distance.

### Understanding the soal:
- Data yang dipake dr tabel cuma item bought dan arrival frequency.
- Because `K = 3`, ada 3 Centroids;
- C1 (2,10); C2 (5,8); C3 (1,2)
- Gunakan rumus:
![image](https://github.com/user-attachments/assets/abadffd2-4994-4135-8c0e-a32c7936a437)

where;
- x2 is X dari Centroid
- x1 is X dari data customer (in this case: item bought)
- y2 is Y dari centroid
- y1 is Y dari data customer (in this case: arrival frqcy)

### Pengerjaan:

![image](https://github.com/user-attachments/assets/a4598d35-3052-4ad5-abd2-6df69307d199)

![image](https://github.com/user-attachments/assets/7af33cdc-1e43-4b79-bd47-68192f4d4a79)

dst until assignments stop changing centroids.

