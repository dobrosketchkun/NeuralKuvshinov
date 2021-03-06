### **[RU]** | [EN](https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/README_EN.md)
---
# Новая версия - [NeuralKuvshinov_v2](https://github.com/dobrosketchkun/NeuralKuvshinov_v2)
---
Как большой поклонник извращенств с нейросетями и творчества [Ильи Кувшинова](https://www.instagram.com/kuvshinov_ilya/) я решил натренировать нейросеть на его работах. Для набора датасета я использовал [instaloader](https://instaloader.github.io/), как начальную нейросеть - [stylegan2-ffhq-config-f.pkl](http://d36zk2xti64re0.cloudfront.net/stylegan2/networks/stylegan2-ffhq-config-f.pkl), а обучалось это всё в [stylegan2-ada](https://github.com/NVlabs/stylegan2-ada).

Результаты оказались интересными и лучше, чем я ожидал. Возможно они были бы ещё лучше, кабы я не кинул первоначально весь дамп инстаграма в нейросеть, а только потом за два эпизода очистки не довёл её только до портретной составляющей.

Для представления полученного я разделил возможные результаты на несколько уровней:

### Top tier

<div align="center">
<img src="https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/high.jpg" width="800">
</div>

### Middle tier

<div align="center">
<img src="https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/middle.jpg" width="800">
</div>

### Low tier

<div align="center">
<img src="https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/low.jpg" width="800">
</div>

## Ну и for fun два бонусных:

### Nightmare tier

<div align="center">
<img src="https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/nightmare.jpg" width="800">
</div>

### Abstract tier

<div align="center">
<img src="https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/abstract.jpg" width="800">
</div>

---
Вот [тут лежат несколько разных моделей](https://drive.google.com/drive/folders/1T6BNlyPpvLsxXI-gkCepR7S_nFcSi63o?usp=sharing) (чем выше номер, тем дольше они обучались).

Чтобы сгенерировать берёте [NeuralKuvshinov.ipynb](https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/NeuralKuvshinov.ipynb) и идёте с ним в [Google Colab](https://colab.research.google.com/)


На закуску видео с прогулкой по top tier с интерполяцией (ведёт на youtube):

[![Neural Kuvshinov interpolation walk](https://github.com/dobrosketchkun/NeuralKuvshinov/blob/main/interpolation_movie.gif?raw=true)](https://www.youtube.com/watch?v=EYCxhISX2wI)
