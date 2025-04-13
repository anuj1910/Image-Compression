# Sparse Matrix Image Compression - CAO Hackathon Project

This project implements a sparse matrix multiplication algorithm for image compression, focusing on efficient compression while preserving image quality. The implementation incorporates Computer Architecture and Organization (CAO) principles for optimal performance.

## Features

- Real-time image compression using sparse matrix representation
- Interactive compression level control
- Side-by-side comparison of original and compressed images
- Zoom tool for detailed pixel-level inspection
- Performance metrics including:
  - Compression ratio
  - PSNR (Peak Signal-to-Noise Ratio)
  - Processing time

## CAO Implementation Details

The project incorporates several Computer Architecture and Organization concepts:

1. **Sparse Matrix Storage**
   - Uses CSR (Compressed Sparse Row) format for efficient storage
   - Optimizes memory usage by only storing non-zero elements

2. **Parallel Processing**
   - Implements SIMD instructions for matrix operations
   - Utilizes parallel processing for faster compression

3. **Cache Optimization**
   - Block-based processing for better cache utilization
   - Minimizes cache misses through optimized data access patterns

4. **Memory Management**
   - Efficient memory allocation for sparse matrices
   - Minimizes memory fragmentation

## How to Use

1. Open `index.html` in a modern web browser
2. Upload an image using the file input
3. Adjust the compression level using the slider
4. Use the zoom tool to inspect image details
5. View performance metrics in real-time

## Technical Implementation

- **Frontend**: HTML5, CSS3, JavaScript
- **Image Processing**: Canvas API for image manipulation
- **Compression Algorithm**: Sparse matrix multiplication with threshold-based compression
- **Performance Metrics**: Real-time calculation of compression ratio and PSNR

## Browser Compatibility

The application is compatible with modern browsers that support:
- HTML5 Canvas
- FileReader API
- ES6 JavaScript features

## Future Improvements

1. Implement GPU acceleration for faster processing
2. Add support for different compression algorithms
3. Implement batch processing for multiple images
4. Add support for different image formats
5. Implement progressive compression for large images

## License

This project is open-source and available under the MIT License. 