# Prompt engineering primer (with MPF)

Welcome to the world of prompt engineering, a fascinating area where we learn how to interact effectively with large language models (LLMs) like ChatGPT. At its core, a "prompt" is simply a question or instruction that we give to an AI. The AI then processes this input and provides us with an answer or performs a specific task based on that input. Using the right prompts can greatly enhance the quality and relevance of the responses we get from the AI.

Prompt engineering is not just about asking questions; it's about asking questions in the right way. By carefully crafting prompts, we can guide the AI to understand not only what we're asking but how we want the information presented. This can be very useful in a wide range of scenarios, from generating creative writing and coding help to providing detailed explanations and personalized advice.

Throughout this primer, we'll be using the Markdown Prompts Framework (MPF). This framework is a simple guide that helps us structure our prompts to get the most out of them, ensuring clarity, precision, and efficiency in our interactions with AI. We'll learn how to build effective prompts step-by-step using MPF, empowering you to harness the full potential of LLMs in your daily tasks or specialized projects.

## What is Markdown Prompts Framework (MPF) and why should you use it

The Markdown Prompts Framework (MPF) is a simple way to organize the information you need to provide when you're creating prompts, which are basically questions or tasks you want help with. Think of it as putting your thoughts into neat boxes so everything is clear and easy to find. By using MPF, you list the actual question you need answered in one section, provide some background or detail in the next, and specify any special requests or limitations after that. This structure isn't about making things look fancy; it’s about clarity. This way, your questions are easier for both people and language-learning models (like AI) to understand and respond to effectively.

Why use the MPF? Because it helps prevent important details from being overlooked and makes sure everything relevant is considered. It's like when you’re cooking and lay out all your ingredients before you start – it makes the process smoother and the outcome better. By organizing your prompts this way, you help ensure that the responses you get are more accurate and useful. Furthermore, this method can save time for everyone involved by reducing confusion and back-and-forth communication. Whether you're asking for help from another person or a computer program, MPF makes the exchange more straightforward and efficient.

## Anatomy of the Markdown Prompts Framework (MPF)

The Markdown Prompts Framework (MPF) is organized into several simple sections, each serving different purposes:

__ASK__: Here, you clearly state what you need. Think of it as asking a question or stating a problem directly, like telling a friend exactly what kind of help you're looking for.

__CONTEXT__: This part provides background or settings for your request. It's like setting the scene in a story to make sure everyone understands the surroundings and reasons behind your question.

__CONSTRAINTS__: Constraints are special rules or limits you set for the answer. Imagine telling someone the rules of a game before you start playing—to make sure they know what's allowed and what's not.

__EXAMPLE__: In this section, you can include a sample answer or an instance that shows what kind of response you’re looking for. It’s like showing a picture to make sure everyone knows what the end result should look like.

__FORMAT EXAMPLE__: Here, you specify how you want the information to be organized. It's like telling someone to write a list instead of a paragraph when giving you instructions.

__STYLE__: The style section describes the tone or manner in which you want the response. It's guiding how someone should talk, like asking them to explain something in a friendly way to a child.

Choosing the right sections in the Markdown Prompts Framework (MPF) helps in shaping the response to match your exact needs. By carefully selecting and detailing each part, you can tailor the outcome to be as useful and relevant as possible for your particular requirement.

You may notice that above, we use the bold text to delineate sections of a prompt. In the MPF, the specific markdown elements used aren't crucial. The structure is what matters. These elements simply help in organizing the content clearly. Other markdown elements that could serve similar purposes include bullet points for lists, italic texts for emphasizing aspects of the prompt, or headers to declare sections. Each contributes to clearer, more structured, and focused prompts.

## Deep dive into element of MPF

### __ASK__ and you shall receive

In the realm of prompt engineering, the "__ASK__" section is fundamentally the heartbeat of your interaction with AI models like ChatGPT. This segment is where you clearly spell out what you need, framing your query or command in no uncertain terms. Picture this as directly asking a friend for a specific type of help; the goal is to be as clear and straightforward as possible to minimize misunderstandings. In practical terms, this means avoiding ambiguity and making sure your request is detailed enough to guide the AI in the right direction from the get-go.

Clarity and directness in the "__ASK__" component are crucial because they define the effectiveness of the AI's response. When the AI fully understands the task at hand, it can apply its capabilities more efficiently and accurately. Consider telling someone to bring you a chair. If you specify "Please bring me a small, red chair from the kitchen," your instructions are clear, and you're likely to get exactly what you need. Similarly, with AI, detailed and direct asks prevent roundabout answers and ensure that the output is as relevant as possible to your needs. This precision not only streamlines the interaction but also enhances the quality of the responses you receive, saving time and reducing the likelihood of follow-up questions.

#### Examples of a bad __ASK__

Bad asks often seem adequate at first but lack specificities that lead to clear, useful responses. Here's how seemingly okay asks can miss the mark and why clarity matters:

| Ask | Analysis |
| --- | --- |
| **Tell me about trees.** | This ask is too vague because 'trees' could refer to anything from types, uses, ecological benefits, or specific species. The AI might provide a general overview that doesn't meet any specific need. |
| **Write something interesting.** | This ask lacks specificity in subject matter and desired outcome. 'Something interesting' can vary widely in interpretation, resulting in content that may not be relevant or engaging to the user's expectations. |
| **Can you help me with my project?** | This ask is ambiguous as it doesn't clarify what type of project or what kind of help is needed. As a result, the AI can't deliver targeted assistance, and further clarification would be necessary. |

#### Examples of a good __ASK__

For good asks in prompt engineering, the target is precision and completeness. Here are examples of good asks, designed to produce specific and helpful responses from an AI model:

| Ask | Analysis |
| --- | --- |
| **Provide a summary of the environmental impact of deforestation in the Amazon rainforest.** | This ask is specific, mentioning both the topic (deforestation) and the location (Amazon rainforest), and what is needed (a summary of environmental impacts). It guides the AI to focus the response appropriately. |
| **Describe three practical ways to improve mental health for remote workers.** | This ask is clear by specifying the subject (mental health), the target group (remote workers), and the required information (three practical ways to improve). This allows the AI to tailor its response directly to the ask. |
| **Can you generate a 500-word essay on the rise and fall of the Roman Empire?** | This ask clearly outlines the essay's topic, desired length, and scope, making it straightforward for the AI to comply with the expectations and deliver precise content. |

### Out of __CONTEXT__, out of mind

In the universe of prompt engineering, setting the "__CONTEXT__" is akin to drawing the map for a treasure hunt. It lays down the foundational scene, providing background information and specifics of the environment where the interaction will take place. Like preparing someone for a scene in a play, here you detail the backdrop against which your "__ASK__" operates. This is crucial because it ensures that the AI understands not just what you are asking, but also where and how it fits into a broader scenario.

The "__CONTEXT__" section is essentially about setting the stage correctly. It provides a focused lens for the AI to view your ask, enabling it to generate responses that are not only accurate but also contextually appropriate. Imagine asking for advice on planting a garden; the advice would differ wildly depending on whether it's a flower garden or a vegetable patch, and whether it's in a tropical climate or a cold region. Similarly, the right context in your prompt helps the AI tailor its responses to match the specifics of your situation, enhancing the relevance and applicability of the output.

#### Examples of poorly set __CONTEXT__

Bad context setups can mislead the AI, resulting in answers that might be correct in a general sense but are inappropriate for the specific scenario at hand. Here’s how ineffective contexts might lead to less targeted AI responses:

| Context | Analysis |
| --- | --- |
| **Consider a high school project requirement.** | This context is vague as it doesn't specify what subject or type of project (e.g., science fair, history report) the high school requirement pertains to, leading to a broad and possibly irrelevant guidance. |
| **Think about professional work in an office.** | This context lacks specifics about the type of profession or the kind of office environment (e.g., creative agency, law firm), which could vastly change the nature of the expected advice or content. |
| **Assuming participation in a sport.** | Without specifying the sport (e.g., soccer, swimming, chess), the strategies or relevant advice could end a good fit for some sports but completely irrelevant for others. |

#### Examples of effectively set __CONTEXT__

A well-crafted context sets the exact parameters needed for the AI to understand the nuances of the request. Here are examples where a well-defined context leads to focused and applicable AI responses:

| Context | Analysis |
| --- | --- |
| **Write a travel guide for backpackers visiting Thailand during the monsoon season.** | This context clearly defines the audience (backpackers), the destination (Thailand), and a specific time (monsoon season), allowing for tailored travel advice that addresses challenges and opportunities specific to these conditions. |
| **Discuss strategies for a small local bakery to increase Instagram followers.** | Here, the context specifies the type of business (small local bakery) and the platform of focus (Instagram), which helps the AI provide targeted social media strategies appropriate for that business type and setting. |
| **Explain the challenges of remote learning for elementary school students.** | The context is set around a specific group (elementary school students) and a particular situation (remote learning), enabling AI to zero in on relevant challenges and possibly suggest age-appropriate solutions. |

### Understanding the __CONSTRAINTS__ in Prompt Engineering

In the field of prompt engineering, specifying the "__CONSTRAINTS__" is akin to setting the rules of a game. This segment of the prompt strictly defines the boundaries within which the AI should operate, clearly determining what it can or cannot do in its response. It's similar to giving instructions about what tools or ingredients someone can use when cooking a specific dish. By setting these constraints, you ensure that the AI's responses adhere to certain limitations, whether they are related to the style, length, focus, or specific content that must be included or avoided.

The "__CONSTRAINTS__" element ensures that the AI’s output is not just accurate but also appropriate and suitable for specific needs or platforms. Imagine instructing an artist to paint a landscape but specifying that they can only use watercolors and must finish within two hours. Similarly, imposing constraints on AI helps tailor its creativity and capabilities to fit within desired parameters, improving the utility and relevance of its responses.

#### Examples of poorly specified __CONSTRAINTS__

Vague or missing constraints can lead to outputs that may technically answer the prompt but fail to meet the practical requirements or nuances expected in the response. Here's how ineffective or omitted constraints can cause issues:

| Constraint | Analysis |
| --- | --- |
| **None specified.** | Failing to set any constraints gives the AI no boundaries, leading to responses that might not fit the intended use, such as being too lengthy, not adhering to format requirements, or using undesired styles or tones. |
| **Avoid certain topics.** | This constraint is too vague — not specifying which topics to avoid can cause the AI to unintentionally delve into unwanted or sensitive areas. |
| **Keep it professional.** | While instructing the AI to maintain a professional tone, this lacks clarity on what constitutes 'professional' in different contexts, potentially leading to overly formal or mismatched responses depending on the audience. |

#### Examples of well-set __CONSTRAINTS__

Effective constraints are specific and clear, leaving little room for misinterpretation by the AI, thus ensuring that the output meets the precise needs of the user. Here are examples of well-defined constraints tailored to achieve specific outcomes:

| Constraint | Analysis |
| --- | --- |
| **Respond in simple, everyday language without technical jargon.** | This constraint ensures that the AI uses accessible language that can be easily understood by laypersons, avoiding complex terms that might confuse the intended audience. |
| **Answer should not exceed 200 words.** | Setting a word limit helps keep the AI's response concise and to the point, suitable for situations where brief communication is preferred or required. |
| **Exclude any personal opinions or examples involving real people.** | This constraint guides the AI to maintain objectivity and privacy, making the content appropriate for professional or public informational purposes. |

### __EXAMPLE__, Don't Tell

In the wondrous landscape of prompt engineering, the "__EXAMPLE__" element is the bridge between theory and practice—it brings abstract concepts to life by illustrating practical instances of responses. Much like storytelling enriches a lesson with anecdotes, adding examples helps to shape expectations and elucidate exactly how a properly formulated prompt and its results might look.

The role of the "__EXAMPLE__" segment is critical as it clarifies the expected output format, tone, and content. It allows users or other developers to grasp how specific prompt parameters, such as context and constraints, influence the AI’s responses. This comprehension is pivotal in refining prompts, ensuring not only relevant but also high-quality results.

Creating examples can start with a generic prompt, which is then iterated upon. Initially, you provide a basic prompt to the AI. Once you receive an output, you refine your prompt based on the envisioned requirements or what might be missing in the AI’s response, and feed it again. This iterative approach helps in crafting an example that is closely aligned with the expected outcome.

### Building with __FORMAT EXAMPLE__

In the realm of prompt engineering, the "__FORMAT EXAMPLE__" section is your method of showing a precise template or structure that the response should follow. This is akin to providing a cooking recipe where specific measurements and steps are required to achieve the desired outcome.

The "__FORMAT EXAMPLE__" segment acts as a visual aid or blueprint for the desired format of the output, guiding the AI in structuring its responses according to a predefined layout. It's like setting up a model of a building, ensuring that anyone who follows the blueprint constructs the building similarly.

By using the "__FORMAT EXAMPLE__" segment effectively, users can reduce ambiguity, ensuring that the response not only meets the content needs but also adheres to a specific format, making the data easier to interpret or integrate into subsequent systems or documents.

#### Examples

##### JSON Output

__ASK__
Generate a vehicle's specifications in JSON format with "make", "model", "year", and "color".

__FORMAT EXAMPLE__
```json
{
  "make": "Toyota",
  "model": "Corolla",
  "year": 2020,
  "color": "red"
}
```

##### Markdown Output

__ASK__
List the features of a premium laptop in Markdown format.

__FORMAT EXAMPLE__
```markdown
- **Processor:** Intel Core i7
- **RAM:** 16GB
- **Storage:** 512GB SSD
- **Display:** 14-inch Full HD
```
"""

##### YAML Output

__ASK__
Describe a book in YAML format with "title", "author", "published_year", and "genre".

__FORMAT EXAMPLE__
```yaml
title: "1984"
author: "George Orwell"
published_year: 1949
genre: "Dystopian Fiction"
```

### Crafting Your __STYLE__

In the intricately woven world of prompt engineering, understanding and setting the "__STYLE__" element is akin to choosing the perfect outfit for an occasion. This segment defines the manner in which the AI should present its response, shaping the language, tone, and structure to fit the intended audience and purpose. Just as you wouldn't wear flip-flops to a formal dinner, the style of communication should appropriately match the setting and expectations of your audience.

The "__STYLE__" section is crucial because it directly influences the perception of the AI's response. It ensures that the presentation of information is not only accurate but also palatable and engaging for the intended audience. Whether you seek a professional report, a casual blog post, or an educational tutorial, defining the style helps tailor the AI's output to be more effective and audience-appropriate.

"Tone," "language," and "length" are fundamental elements of the "__STYLE__" section. Tone relates to the emotional inflection and attitude of the text — is it formal, enthusiastic, or somber? Language involves choosing simple or complex vocabulary, technical terms, or everyday speech that makes the content accessible or sophisticated. Length dictates the brevity or expansiveness of the response — whether a succinct summary or a detailed exploration is required. Together, these factors help sculpt the user's actual experience of the AI's output, making it engaging and appropriate for their needs.
