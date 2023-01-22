<h1 align="center">
  <br>
  <a href="https://pytorch.or"><img src="https://pytorch.org/tutorials/_static/img/thumbnails/cropped/profiler.png" alt="Torch" width="200"></a>
  <br>
  Hand written number recognition
  <br>
</h1>

<h4 align="center">A Deep Learning CNN model for hand signs number recognition. 
</h4>

<p align="center">
  <a href='https://pytorch.org/' target="_blank"><img alt='pytorch' src='https://img.shields.io/badge/pytorch-100000?style=for-the-badge&logo=pytorch&logoColor=FF5100&labelColor=F1F1F1&color=E4E4E4'/></a> <a href='' target="_blank"><img alt='python' src='https://img.shields.io/badge/python-100000?style=for-the-badge&logo=python&logoColor=FFEB0D&labelColor=244EFA&color=4180FF'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a> 
</p>

![screenshot](https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F66babb47-0e17-4f08-9a68-4945d78ef5db%2FUntitled.png?id=c728ab17-b1f8-42b2-b4b7-17566ad1c081&table=block&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=2000&userId=&cache=v2)

## Key Features

This deep learning NN architecture predicts digit from a hand number sign. This prediction is a number between 0 and 5. So here are the key features of this project:

* Dataset:
  - Contains 864 train images whose resolution is 64 x 64 
  - `Can be downloaded cloning this repo.
* Convolutional Neural Network:
	- The model is a subclass of the class `torch.nn.Module`.
	- Contains 3 Convolutional layers, 2 Fully connected layers and max pooling layers. Also we used the `ReLU` activation function
* We archieved a 96.8% of accuracy.

## How To Use

To clone and run this application, follow these steps

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/Hand-number-recognition-with-pytorch.git

# Go into the repository
$ cd Hand-number-recognition-with-pytorch

# Install dependencies
$ pip install -r requirements.txt

# Go to the notebooks dir
$ cd notebooks

# Open Jupyter Notebooks

$ jupyter-notebook
```


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
