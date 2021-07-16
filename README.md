# Task_3_YOLOv5

- YOLOv5 utilizando DeepSORT (https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch/tree/master/deep_sort_pytorch).
- Colocar o arquivo detect_track.py e o repositório do DeepSORT na pasta da YOLOv5 e executar.

Comando para executar:

```py
python path/to/detect_track.py --source path/to/video.mp4 --weights path/to/best.pt
```

Para este script, usei como base o seguinte projeto: https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch.git 

Com esta resolução, é possivel detectar e rastrear objetos. Entretanto, deixei comentado o trecho do código que apresenta as caixas delimitadoras da detecção, para que as mesmas não fiquem sobrepostas com as caixas delimitadoras do track.

![track](https://user-images.githubusercontent.com/78621851/126008179-4d5baf87-52da-4e54-86d0-b6e199aaae8b.gif)
