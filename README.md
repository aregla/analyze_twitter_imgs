## Analyzing posts from Twitter using OpenAI GPT-4-Vision Model
### Description of approach
To investigate the impact of hashtags on shaping social movements through Twitter imagery, our methodology integrates advanced image analysis with the capabilities of the GPT-4 Vision API. Initially, we curated a dataset of 500 images from Twitter posts before and after a significant event, aiming to capture the visual narrative of social movements. These images were processed using a custom Python script to ensure compatibility with the GPT-4 Vision API. This script performed image resizing to a maximum dimension of 512 pixels to meet API constraints, maintaining the integrity of visual details while optimizing for processing efficiency.
For each image, the GPT-4 Vision API was tasked to generate detailed textual descriptions and identify main themes. This was achieved through a predefined prompt, directing the model to provide comprehensive narratives and thematic analyses. The process involved encoding each image to a base64 string, facilitating its submission to the API alongside the instructional prompt. The API's responses were parsed to separate image descriptions from identified themes, utilizing a structured approach to ensure consistency and reliability in data extraction.
Subsequently, the extracted data—comprising image paths, descriptions, and themes—were systematically compiled into a DataFrame. This facilitated an organized dataset ready for analytical exploration, enabling the examination of thematic shifts in social movements' visual representation on Twitter. The entire dataset was then exported to a CSV file for further analysis and archiving purposes.
This methodology underscores a novel approach to understanding social movements through digital imagery on social media platforms. It leverages cutting-edge AI capabilities to interpret and quantify visual data, offering insights into the dynamics of social mobilization and the symbolic significance of hashtags in contemporary digital discourse.

- [Link to Google Drive folder with images](https://drive.google.com/drive/u/0/folders/1FQzKDp7G2I4ueQOgH9VYd6UCcDNGXNgx)
- Link to GitHub repository with notebook

### Resources
- [Image openai cookbook example](https://cookbook.openai.com/examples/tag_caption_images_with_gpt4v)
- [Openai cookbook example for video](https://cookbook.openai.com/examples/gpt_with_vision_for_video_understanding)


