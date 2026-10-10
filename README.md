# Face Swap from Video

This project provides a tool for swapping faces within video content using machine learning and AI technologies. It is intended for responsible use in creative, research, and educational settings.

## Repository

- GitHub: https://github.com/ramim-kobir/Face-swap-from-video

## Quick start

### Clone

```bash
git clone https://github.com/ramim-kobir/Face-swap-from-video.git
cd Face-swap-from-video
```

### Google Colab

```python
!git clone https://github.com/ramim-kobir/Face-swap-from-video.git
%cd Face-swap-from-video
!pip install -r requirements.txt
```

## Usage

```bash
python main.py --source testing/testing.jpg --target testing/testing.mp4 --output output.mp4 --fps 30
```

## Notes

- Use Python 3.8 to 3.11.
- For CUDA-enabled systems, install the GPU build of onnxruntime if needed.
- Keep all source images and target videos in the expected local paths before running the script.

## Ethical Use Guidelines

1. Consent: Always ensure that individuals whose faces are being swapped have given explicit, informed consent for their likeness to be used.
2. Transparency: Clearly inform others that face-swapping technology has been used in your video or content.
3. Non-Exploitation: Do not use this tool to create content that could harm, harass, or exploit others.
4. Legal Compliance: Follow the laws regarding privacy, copyright, and data protection in your jurisdiction.

## Disclaimer

The developer of this project does not take responsibility for any misuse of the tool. Users of this project are responsible for complying with applicable laws and ethical standards.
