# uv-pep723-scripts

A collection of useful python scripts with the PEP 723 header in mind to avoid having to install dependencies, `uv` can
handle these. These scripts are inspired by this blog
post: [Fun with uv and PEP 723](https://www.cottongeeks.com/articles/2025-06-24-fun-with-uv-and-pep-723).

## Pre-requisites

- Install [uv](https://docs.astral.sh/uv/getting-started/installation/).
- Use an `.env` file for specific environment variables, for example:
    ```env
    OPENAI_API_KEY=...
    OPENAI_BASE_URL=...  # optional
    MODEL_NAME=...  # optional, defaults to `gpt-4o`
    ```
- Copy the scripts to ~/.local/bin/ or any other directory in your `PATH`.

## Usage

```shell
ytt https://www.youtube.com/watch\?v\=Bzgt2HKWmHY | summarize
```
```text
The speaker critiques the current state of AI products from big tech companies like Microsoft (Co-Pilot), Google
(Gemini), and Apple (Apple Intelligence), arguing that many are "solutions without a problem" and primarily serve as
tools for data collection and monetization rather than genuine user benefit. While acknowledging that some AI
applications, such as code assistance and image editing, are genuinely useful, the speaker warns that widespread system
integration often comes at the cost of user privacy, as these tools absorb large amounts of personal data to improve
their algorithms and target advertising. The video emphasizes skepticism toward the marketing of AI, encourages users to
seek alternatives to big tech ecosystems, and expresses hope for the future through emerging technologies and the
ingenuity of new generations. The speaker plans future content on self-hosted and open-source alternatives, urging users
to reclaim value and autonomy from monopolistic tech giants.
```
