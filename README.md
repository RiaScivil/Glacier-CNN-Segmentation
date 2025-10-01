# Glacier-CNN-Segmentation
This repository implements a complete deep learning pipeline for glacier segmentation using Roboflow imagery, Google Earth Engine satellite data, and an attention-based U-Net model. Includes real-time monitoring via FastAPI.
<img width="1536" height="1303" alt="image" src="https://github.com/user-attachments/assets/4b754a2a-0f3f-47ea-9de1-df35adde6f5b" />
<img width="913" height="639" alt="image (1)" src="https://github.com/user-attachments/assets/54b8d190-2df7-4951-9982-b1d5ff49f0f4" />

## Project Structure
- **data/**: Instructions and placeholders for datasets
- **scripts/**: Python scripts for data prep, model training, deployment
- **models/**: Model architectures and trained weights
- **api/**: FastAPI app for deployment
- **requirements.txt**: Python dependencies
- **Dockerfile**: For scalable containerized deployment

## Setup
1. Install dependencies
2. 2. Download and organize your glacier datasets in the `data/` folder, or set up links to Roboflow workspace exports.
3. Run model training
4. Deploy the real-time API
## License
This project is licensed under CC BY 4.0 or MIT. See LICENSE for details.
