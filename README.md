# YouTube Video Summarizer and Quiz Generator

This project is a Python-based tool that creates a summary and generates a quiz based on the transcript of a YouTube video. It uses natural language processing techniques to process the video transcript, create a summary, and generate multiple-choice questions.

## Features

- Retrieves transcripts from YouTube videos
- Generates a summary of the video content
- Creates multiple-choice questions based on the summary
- Provides an interactive quiz experience
- Calculates and displays the user's score

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- pip (Python package manager)

## Installation

1. Clone this repository: git clone https://github.com/RishabhGithub7348/YouTube-Video-Summarizer-and-Quiz-Generator.git
   cd youtube-summarizer-and-quiz-generator
3. Install the required packages: pip install youtube_transcript_api transformers torch nltk

 ## Usage

1. Run the main script:
2.  When prompted, enter a YouTube video URL.

3. The program will generate a summary of the video and create 3 multiple-choice questions.

4. Answer the questions as they appear.

5. After completing the quiz, you'll receive your score.

## How It Works

1. **Transcript Retrieval**: The script uses the `youtube_transcript_api` to fetch the video's transcript, prioritizing English subtitles when available.

2. **Text Summarization**: It employs a pre-trained T5 model from the `transformers` library to generate a concise summary of the transcript.

3. **Question Generation**: Using NLTK for natural language processing, the script creates multiple-choice questions based on the summary.

4. **Quiz**: The user is presented with the questions and can input their answers.

5. **Scoring**: The script calculates and displays the user's score at the end of the quiz.

## Project Structure

- `main.py`: The main script containing all the functions and logic.
- `requirements.txt`: List of Python packages required for this project.
- `README.md`: This file, containing project information and instructions.

## Contributing

Contributions to this project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively, see the GitHub documentation on [creating a pull request](https://help.github.com/articles/creating-a-pull-request/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [youtube_transcript_api](https://github.com/jdepoix/youtube-transcript-api) for YouTube transcript retrieval
- [Hugging Face Transformers](https://github.com/huggingface/transformers) for text summarization
- [NLTK](https://www.nltk.org/) for natural language processing tasks

## Contact

If you want to contact me, you can reach me at `rishabhmaurya7654@gmail.com`.

   
