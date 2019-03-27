onlineMNIST
===========

Recognise hadwriten digits using your browser.

Try the [online demo](https://gnuevo.github.io/onlineMNIST/index.html).


## Motivation

Rather than classifying MNIST numbers -- thing that to the best of my knowledge has been done gazillions of times -- here I propose a different approach.
The classification is not the important part.
What is important is that you can recognise the digits using your browser.
Yes, that's it.
No downloading frameworks, no `git clone` the repo, no install dependencies, etc.
Just open [this link](https://gnuevo.github.io/onlineMNIST/index.html) in your browser, click the "Download" button to get the pretrained network (wait till it's "Done") and you're ready to write digits using the mouse or your fingers.

### Limitations

Despite performing quite well on the test set (it's good old MNIST after all), the recognition of digits in the brower fails sometimes and for samples that seem too obvious!
I think this is because MNIST is a clean dataset (all digits are centered, straight and with a similar size) whereas writing digits with a mouse or a finger on a white square doesn't generate such good samples.
