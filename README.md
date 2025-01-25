# Image-Informatics
This project focuses on  creating custom algorithm for image reading, followed by Haar wavelet transformation. The workflow includes wavelet denoising with VisuShrink thresholding, mean, median, and NL-means filtering, and weighted average fusion, achieving improved image clarity and effective noise handling.

---

# Image Processing and Noise Reduction  

## Overview  
This project explores image processing techniques to enhance image clarity by identifying and reducing noise. It includes a custom image reading algorithm, wavelet transformations, and advanced filtering techniques to handle various noise types effectively.  

## Features  
- **Custom Image Reader**: Algorithm to read images and address common challenges.  
- **Haar Wavelet Transformation**: Multi-level transformation to analyze image details.  
- **Wavelet Denoising**: Noise reduction using forward wavelet transformation and VisuShrink thresholding.  
- **Advanced Filtering**: Techniques like mean, median, and NL-means filtering.  
- **Weighted Average Fusion**: Combines results for enhanced clarity and accuracy.  

## Workflow  
1. Read the image using a custom algorithm.  
2. Apply Haar wavelet transformation to extract components.  
3. Perform noise filtering using:  
   - Forward wavelet transformation.  
   - VisuShrink thresholding for components.  
   - Inverse wavelet transformation.  
4. Further refine using mean, median, and NL-means filtering.  
5. Fuse results with weighted average logic to achieve optimal output.  

## Results  
The combined approach significantly reduces noise, ensuring better image quality while maintaining details.  

## Installation  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/repo-name.git  
   ```  


## Dependencies  
- Python 3.x  
- NumPy  


## References  
- Research papers on wavelet denoising and noise filtering techniques.  

## License  
This project is licensed under the MIT License.  

## Contributing  
Feel free to submit issues or pull requests to improve this project.  

---  

