🎨 AI Art Generator with Stable Diffusion
Generate stunning images using diffusion models!

This project leverages the power of Stable Diffusion to create AI-generated art from text prompts. Experiment with creative prompts, fine-tune parameters, and explore the intersection of machine learning and digital artistry.

✨ Key Features
Text-to-Image Generation: Turn prompts like "a cyberpunk cat wearing sunglasses" into high-quality images.

Prompt Engineering: Optimize prompts and negative prompts for precise results.

Customizable Parameters: Adjust resolution, guidance scale, and inference steps.

GPU/CPU Support: Runs on both GPU (fast) and CPU (slower).

🛠️ Tech Stack
Python + PyTorch

Diffusers library by Hugging Face 🤗

Stable Diffusion v1-5 and v2-1 models

🚀 Quick Start
Clone the repository:

bash
git clone https://github.com/yourusername/stable-diffusion-art-generator.git  
cd stable-diffusion-art-generator  
Set up a virtual environment:

bash
conda create -n sd_env python=3.10  
conda activate sd_env  
pip install -r requirements.txt  
Run the generator:

python
python generate.py --prompt "a serene lake at sunset, digital art" --negative_prompt "text, blurry" --height 768  
📝 Example Prompts
"A futuristic cityscape with flying cars, neon lights, 8k resolution"  
"An astronaut riding a horse in a watercolor style"  
"A steampunk robot in a lush jungle, intricate details"  
⚙️ Customization
Adjust resolution: --height 512 --width 768

Control creativity: --guidance_scale 15 (strict) or --guidance_scale 3 (creative)

Speed vs. quality: --num_inference_steps 30 (faster) or --num_inference_steps 100 (higher detail)

📸 Sample Outputs
Cyberpunk Cat 🐱	Fantasy Landscape 🌄	Steampunk Airship 🚀
<img src="samples/cyberpunk_cat.png" width="200">	<img src="samples/landscape.png" width="200">	<img src="samples/airship.png" width="200">
📌 Ethical Note
Generated images may inherit biases from the training data. Use responsibly and avoid harmful content.

🔗 Resources
Stable Diffusion Documentation

Prompt Engineering Guide
