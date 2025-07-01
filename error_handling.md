# Error Handling Guidelines

## Invalid or Private Video
- **Error**: Video URL is invalid, private, or restricted.
- **Action**: Return message: "Unable to access video. Please ensure the URL is valid and the video is public."
- **Fallback**: Prompt user to provide a manual transcript or alternative URL.

## No Subtitles Available
- **Error**: Video lacks subtitles or transcript.
- **Action**: Use speech-to-text (e.g., pydub or Google Cloud Speech-to-Text) to generate a transcript from audio.
- **Fallback**: Inform user: "No subtitles available. Audio-based transcript generated. Accuracy may vary."

## API Rate Limit Exceeded
- **Error**: Gemini API rate limit (e.g., 50 requests/day) exceeded.
- **Action**: Cache recent transcripts/metadata and retry after delay.
- **Fallback**: Suggest user upgrade to a paid plan or wait for reset.

## Unsupported Language
- **Error**: Video transcript is in an unsupported language.
- **Action**: Use Gemini’s translation capabilities to convert to English before summarization.
- **Fallback**: Inform user: "Unsupported language detected. Translation applied. Results may vary."
