# YouTube Video Downloader

This project provides a simple and effective way to download YouTube videos using Google Colab and the `pytube` library. 

## Features
- Download YouTube videos in the highest resolution available.
- Easy to use with minimal setup.
- Runs entirely in Google Colab.

## Getting Started

### Prerequisites
- Google Colab
- Python 3.x

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/youtube-video-downloader.git
    ```
2. Open the `download_youtube_video.ipynb` notebook in Google Colab.

3. Install the required Python packages:
    ```python
    !pip install -r requirements.txt
    ```

### Usage

1. Open `download_youtube_video.ipynb` in Google Colab.

2. Install `pytube` by running the first cell:
    ```python
    !pip install pytube
    ```

3. Run the code cell that contains the download function.

4. Replace the placeholder URL with your desired YouTube video URL and execute the final cell to download the video:
    ```python
    video_url = 'https://www.youtube.com/watch?v=YOUR_VIDEO_ID'  # Replace with your YouTube video URL
    download_youtube_video(video_url, output_path='/content')
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
