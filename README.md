# NEURAL-STYLE-TRANSFER

**COMPANY NAME** : CODTECH IT SOLUTIONS PVT.LTD

**INTERN NAME**: SHAIK MUSHARAF

**INTERN ID**: CT08DM690

**DOMAIN**:ARTIFICIAL INTELLIGENCE

**DURATION**: 8 WEEKS

**MENTOR**: NEELA SANTHOSH

# DESCRIPTION:
The Neural Style Transfer Model is a Python script designed to artistically transform photographs by applying the visual style of one image (the "style image") to the content of another image (the "content image"). The result is a unique output image that blends the subject matter of the photograph with the aesthetic characteristics of the painting.

## Here's an overview of its core functionality:

- **Content and Style Extraction**: It uses a pre-trained VGG19 Convolutional Neural Network (CNN) to extract distinct feature representations. Deeper layers of the VGG network are used to capture the high-level structural    content" of the photograph, while multiple layers across the network are used to extract the "style" (textures, colors, brushstrokes) from the artistic image.
* **Loss-Based Optimization**: The transformation is achieved through an iterative optimization process. A new, generated image is initialized (typically as a copy of the content image) and then continuously adjusted to minimize a combined loss function. This function consists of:
- **Content Loss**: Ensures the generated image maintains the structural integrity and objects of the original photograph.
Style Loss: Utilizes "Gram Matrices" to match the stylistic patterns and textures of the style image.
- **Total Variation Loss**: A regularization term that helps reduce noise and promotes visual smoothness in the final output.
+ **Iterative Refinement**: The generated image is iteratively updated using an optimizer (like Adam) to reduce the overall loss. This process continues for a specified number of iterations, gradually blending the content and style.

**Purpose:**

This tool serves as a practical demonstration of neural style transfer, allowing users to:

- Experiment with applying various artistic styles to their own images.
- Explore a fascinating application of deep learning in computer vision and computational creativity.
- Understand the underlying principles of how neural networks can learn and combine visual representations.
The script is tailored for use in Google Colab, allowing users to easily upload their own content and style images directly within the notebook environment.
# output:
---
![Screenshot 2025-07-07 174022](https://github.com/user-attachments/assets/b31e79a7-68f4-4bf2-a6c1-96a2409a0c08)

