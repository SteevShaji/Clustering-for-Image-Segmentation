# 📸 K-Means Clustering for Image Segmentation

This project applies **K-Means Clustering** to segment an image into two distinct regions based on pixel colors.  
Instead of capturing from a webcam, this implementation allows **uploading an image from your computer** in **Google Colab**.

---

## **📌 Project Steps**
1. **Upload an Image** from your local computer.
2. **Flatten Image Data** so each pixel is treated as a datapoint with 3 features (R, G, B).
3. **Apply K-Means Clustering** with `n_clusters=2` to group pixels into two clusters.
4. **Mask One Cluster** by assigning a fixed RGB color (e.g., `(255, 255, 255)` white).
5. **Reshape Data** back to the original image dimensions.
6. **Visualize** both the original and segmented images side by side.

---

## **🛠 Technologies Used**
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab (for running the notebook)

---

## **📂 Files in this Repository**
- `KMeans_Image_Segmentation.ipynb` → Jupyter Notebook with the complete code.
- `README.md` → This documentation file.
- *(Optional)* Sample images for testing.

---

## **🚀 How to Run the Project**
1. Open **Google Colab**: [https://colab.research.google.com](https://colab.research.google.com)
2. Upload the `KMeans_Image_Segmentation.ipynb` notebook.
3. Run the notebook cell by cell.
4. When prompted, **upload your image** from your computer.
5. The output will display the **original image** and the **segmented image**.

---

## **📷 Example Output**
| Original Image | Segmented Image |
|----------------|-----------------|
| ![Original](example_original.jpg) | ![Segmented](example_segmented.jpg) |

*(Replace the example images with your actual results if you want)*

---

## **📜 License**
This project is created for educational purposes as part of a Paatshala assignment.
