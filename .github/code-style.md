If you use the openai api, I want you to use the new response API and not the old chat completions api. Here is an example of how to use the API:

from openai import OpenAI
from dotenv import load_dotenv

load_dotenv()

const response = await client.responses.create({
    model: "gpt-4o",
    input: "Write a one-sentence bedtime story about a unicorn.",
});

console.log(response.output_text);
