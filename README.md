# 图生视频模型测试对比

## 图1

<img src="https://github.com/user-attachments/assets/a24bc904-c947-442f-8d3c-5e8d3a05aa82" alt="动漫角色2" width="300" />

### 可灵

```
描述：人物转过身
```

<img src="https://github.com/user-attachments/assets/b5899913-fe95-4eaf-9d70-f7d3b5a3ff2a" alt="可灵1" width="300" />

### Luma

```
描述：Person turns around
```

<img src="https://github.com/user-attachments/assets/42737efc-0fbe-479e-85bd-91fce169ae0d" alt="luma1" width="300" />

### Runaway Gen-2

```
描述：a woman in the leather coat turned around
```

<img src="https://github.com/user-attachments/assets/ecd12bb6-8f83-474f-a06d-40953c43128a" alt="runaway1" width="300" />

### Pika

```
描述：a woman in the leather coat turned around
```

<img src="https://github.com/user-attachments/assets/03f533ff-447b-4101-a5c8-758e0d0d6d8d" alt="pika1" width="300" />

### DynamiCrafter

```
（这里换了一张图像）描述：girl turning around
```

<img src="https://github.com/user-attachments/assets/9c321eee-e2e6-477d-a802-b335044e5401" alt="DynamiCrafter1" width="300" />

### I2VGen-XL

```
（这里换了一张图像）描述：girl turning around
```

<img src="https://github.com/user-attachments/assets/820f378a-07e3-4340-8dac-2ffb12304078" alt="I2VGen-XL1" width="300" />

### 总结

1. 可灵效果最好，通过简单的提示词即可生成视频。Luma、Runaway Gen-2和Pika需要多次调整提示词，但生成效果受限，可能由于模型对于“turn around”词组的训练数据较少等原因。
2. 受模型像素限制影响，DynamiCrafter和I2VGen-XL两个开源模型都无法对图1生成基本的人物视频，模型效果较差。故换用符合模型像素的图片，但也没有生成良好的效果。

## 图2

<img src="https://github.com/user-attachments/assets/d2262f41-0df4-4c14-8288-f76e6b093072" alt="动漫角色4" width="300" />

### 可灵

```
描述：女孩走
```

<img src="https://github.com/user-attachments/assets/fe565ea4-e956-40c1-b248-098101fd0af2" alt="可灵2" width="300" />

### Luma

```
描述：a girl in the dress is walking forward
```

<img src="https://github.com/user-attachments/assets/c0c58a01-29be-4f7d-9dbb-2788c77c18d8" alt="luma2" width="300" />

### Runaway Gen-2

```
描述：a girl in the dress is walking forward
```

<img src="https://github.com/user-attachments/assets/e3df4d07-f1f5-4e3d-9354-5c87af2ead11" alt="runaway2" width="300" />

### Pika

```
描述：a girl with long blue hair in a dress is walking forward
```

<img src="https://github.com/user-attachments/assets/cca31993-15a0-4493-9dfe-f0ef92f3abd7" alt="pika2" width="300" />

### DynamiCrafter

```
描述：girl walking
```

<img src="https://github.com/user-attachments/assets/a5d69f38-225f-4447-a52b-68c7103415f8" alt="DynamiCrafter2" width="300" />

### I2VGen-XL

```
描述：girl walking
```

<img src="https://github.com/user-attachments/assets/b31ab200-956f-4ec3-8a30-eeaeb96f01ba" alt="I2VGen-XL2" width="300" />

### 总结

1. 可灵效果最好，通过简单的提示词即可生成视频。Luma、Runaway Gen-2、Pika和DynamiCrafter需要调整提示词，可以生成较好的效果。
2. 受模型效果，提示词等影响，I2VGen-XL开源模型都无法生成基本的人物视频，效果较差。
