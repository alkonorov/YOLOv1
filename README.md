# YOLOv1
## YOLOv1 architectury PyTorch implement
Реализация архитектуры YOLOv1 для задачи детекции одного класса (person)<br>
**Вид архитектуры:**
![Вид архитектуры](images/YOLO-Full-Model-Architecture.png)

Предсказание модели (на выходе): размерность 5 x B (Bounding Boxes) . Содержит координату центра Bounding box X, координату центра Y, w,h (ширина , высота) , conf ( уверенность в предсказании) а так же набор вероятностей для каждей ячейки grid cell

**Функция потерь**<br>
![Функция потерь](images/loss.png)


## Примеры предсказания созданой и обученой модели: <br>
**неплохие примеры**<br>
<img src="images/inference_000000092021.jpg" width="448">
<img src="images/inference_000000005719.jpg" width="448"> </br>
<img src="images/inference_000000493116.jpg" width="448">
<img src="images/inference_000000123826.jpg" width="448"></br>
<img src="images/inference_000000231598.jpg" width="448"> 
<img src="images/inference_000000217764.jpg" width="448"> </br>
<img src="images/inference_000000262871.jpg" width="448">
<img src="images/inference_000000355282.jpg" width="448"> </br>
<img src="images/inference_000000418464.jpg" width="448"> 
<img src="images/inference_000000429031.jpg" width="448"> 
 </br>


**Плохие примеры**<br>
 </br>
<img src="images/inference_000000098735.jpg" width="448"> 
<img src="images/inference_000000168057.jpg" width="448"></br>
<img src="images/inference_000000246681.jpg" width="448"> 
<img src="images/inference_000000426603.jpg" width="448"> </br>
<img src="images/inference_000000423905.jpg" width="448">
<img src="images/inference_000000546645.jpg" width="448">


