
# VSV-1100: Vietnamese social voice dataset
## Introdution

This dataset includes over 1,100 hours of speech data. The voice samples were collected from a variety of social resources, ensuring a diverse representation of accents, dialects, and speaking styles. This diversity makes the dataset particularly valuable for training and evaluating ASR models, as it enhances their ability to accurately recognize and transcribe speech across different linguistic and cultural contexts.

### Statistics
- Number of samples: 1,026,047
- Sampling rate: 16000
- Size: 131 GB


### Example
```
{'audio': {'path': None,
           'array': array([....]),
           'sampling_rate': 16000},
 'transcription': 'bạn có thể tìm ra cách khắc phục giai đoạn hai và ba tốt hơn'} 
```

### Usage

```python
from datasets import load_dataset
ds = load_dataset("NhutP/VSV-1100", split= 'train')
audio_array = ds[0]['audio']['array']
transcription = ds[0]['transcription']
```


## Contributors
 
- [Pham Quang Nhut](https://github.com/NhutP) 
- [Duong Pham Hoang Anh](https://github.com/HoangAnh109)
- [Nguyen Vinh Tiep](https://github.com/tiep-mmlab)


## Citation

```
@misc{VSV-1100,
    author = {Pham Quang Nhut and Duong Pham Hoang Anh and Nguyen Vinh Tiep},
    title = {VSV-1100: Vietnamese social voice dataset},
    url = {https://github.com/NhutP/VSV-1100},
    year = {2024}
}
```
Also, please give us a star on github: https://github.com/NhutP/VSV-1100 if you find our project useful


Contact me at: 22521061@gm.uit.edu.vn (Pham Quang Nhut)
