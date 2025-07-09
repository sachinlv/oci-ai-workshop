# OCI AI Workshop - Data Science

This repository contains Jupyter notebooks for an AI workshop focused on Oracle Cloud Infrastructure (OCI) Data Science service.

## Prerequisites

Before running the notebooks, ensure you have:
- An active Oracle Cloud Infrastructure (OCI) account
- Appropriate permissions to create and manage Data Science resources
- Basic knowledge of Python and machine learning concepts

## Setup Oracle OCI Data Science Service

### 1. Create a Data Science Project

1. Navigate to the OCI Console
2. Go to **Analytics & AI** > **Data Science**
3. Click **Create Project**
4. Provide a name and description for your project
5. Select the appropriate compartment
6. Click **Create**

### 2. Create a Notebook Session

1. Within your Data Science project, click **Create Notebook Session**
2. Configure the following settings:
   - **Name**: Provide a descriptive name for your session
   - **Compute Shape**: Choose appropriate compute resources (recommended: VM.Standard2.4 or higher for deep learning tasks)
   - **Block Storage**: Allocate sufficient storage (minimum 100GB recommended)
   - **Networking**: Configure VCN and subnet settings
3. Click **Create**
4. Wait for the notebook session to become **Active** (this may take several minutes)

### 3. Access the Notebook Session

1. Once the session is active, click **Open**
2. This will launch JupyterLab in a new browser tab
3. Upload the notebooks from this repository to your JupyterLab environment

## Available Notebooks

### transfer_learning_vgg19.ipynb

This notebook demonstrates transfer learning using the VGG19 pre-trained model for image classification on the CIFAR-10 dataset.

**Key Features:**
- Transfer learning implementation with VGG19
- CIFAR-10 dataset preprocessing and augmentation
- Feature extraction approach
- Model training and evaluation
- Visualization of training metrics
- Custom image inference

**Requirements:**
- PyTorch and torchvision
- GPU-enabled compute instance (recommended)
- Approximately 2-3 hours for full training

**Usage:**
1. Open the notebook in your OCI Data Science session
2. Follow the step-by-step instructions
3. Run cells sequentially to train the model
4. Experiment with different hyperparameters and architectures

## Getting Started

1. **Clone or download** this repository
2. **Set up** your OCI Data Science environment following the setup instructions above
3. **Upload** the notebooks to your JupyterLab environment
4. **Install** required dependencies as specified in each notebook
5. **Run** the notebooks cell by cell, following the instructions and explanations

## Best Practices

- Always use GPU-enabled compute shapes for deep learning tasks
- Monitor your resource usage and costs
- Save your work frequently
- Use version control for your modifications
- Clean up resources when not in use to avoid unnecessary charges

## Support

For issues related to:
- **OCI Data Science service**: Consult the [OCI Data Science documentation](https://docs.oracle.com/en-us/iaas/data-science/using/data-science.htm)
- **Technical content**: Review the notebook documentation and comments
- **Oracle Cloud**: Contact Oracle Cloud Support

## Additional Resources

- [OCI Data Science Documentation](https://docs.oracle.com/en-us/iaas/data-science/using/data-science.htm)
- [OCI Data Science Examples](https://github.com/oracle/oci-data-science-ai-samples)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [Transfer Learning Tutorial](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html)
