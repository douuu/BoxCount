## Box-counting 2D images to compute the fractal dimension ##

This is a simple implementation of Hausdorff dimension computation using the box-counting method.

An example of the computation process can be seen below.

![](https://galileounbound.files.wordpress.com/2020/12/image-16.png?w=512)

## Usage and restrictions ##
- The algorithm converts non-white pixels to one and other pixels to zero.
- To be more precise about the result, it only accepts NxN images as input.

**Example usage**,

    from ImageFractalDimension import ImageFractalDimension

	image = ImageFractalDimension('sierpinski_512x512.png', 512)
    # print(image.fractal_dim)
    image.graph()

**Output**:

![Imgur](https://i.imgur.com/zJYjLEZ.png)