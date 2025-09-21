
# 100 Important MCQs on Prompt Engineering

## Basic Concepts (1-15)

**1. What is prompt engineering?**

A. Programming AI models from scratch

B. The art and science of crafting instructions that guide AI language models to produce desired outputs

C. Hardware optimization for AI systems

D. Database design for AI applications

**2. How do Large Language Models fundamentally work?**

A. They understand text like humans do

B. They are sophisticated autocomplete systems that predict the next most likely word/token

C. They store and retrieve information from databases

D. They use rule-based logic systems

**3. What is the difference between prompt engineering and context engineering?**

A. Prompt engineering is for images, context engineering is for text

B. Prompt engineering crafts instructions, context engineering curates the information the model can see

C. They are the same thing

D. Prompt engineering is outdated, context engineering is modern

**4. What temperature setting would you use for math problems?**

A. High (0.8-1.0)

B. Medium (0.4-0.7)

C. Low (0-0.3)

D. Temperature doesn't matter for math

**5. What is the recommended temperature for creative writing?**

A. 0

B. 0.7

C. 1.5

D. Temperature should be disabled

## Prompting Techniques (6-25)

**6. What is zero-shot prompting?**

A. Providing multiple examples before asking

B. Asking directly without examples

C. Using no prompts at all

D. Setting temperature to zero

**7. How many examples should you typically use in few-shot prompting?**

A. 1-2 examples

B. 3-5 examples

C. 10+ examples

D. As many as possible

**8. What is the purpose of system prompting?**

A. To debug the AI system

B. To set overall context and behavior guidelines

C. To reduce computational costs

D. To increase response speed

**9. Which phrase is commonly used to trigger Chain of Thought reasoning?**

A. "Be creative"

B. "Let's think step by step"

C. "Answer quickly"

D. "Use simple language"

**10. What is role prompting?**

A. Asking about theatrical roles

B. Assigning a specific character or expertise to the AI

C. Defining user permissions

D. Setting access controls

**11. When should you use Chain of Thought prompting?**

A. For simple factual questions

B. For complex problems requiring step-by-step reasoning

C. For creative writing only

D. Never, it's outdated

**12. What is self-consistency in prompting?**

A. Using the same prompt repeatedly

B. Generating multiple reasoning paths and selecting the most common answer

C. Maintaining consistent formatting

D. Using consistent vocabulary

**13. What is step-back prompting?**

A. Going back to previous conversations

B. Asking a more general question first, then using that context for the specific question

C. Reducing the complexity of prompts

D. Using backwards reasoning

**14. What does ReAct stand for?**

A. Reaction + Action

B. Reasoning + Acting

C. Response + Activity

D. Real + Acting

**15. What is Tree of Thoughts (ToT) used for?**

A. Simple classification tasks

B. Exploring multiple reasoning branches simultaneously for complex problems

C. Organizing file structures

D. Network topology design

## Best Practices (16-35)

**16. Which is better prompt structure?**

A. "Write about dogs"

B. "Write a 300-word informative article about health benefits of owning a dog, focusing on mental health"

C. "Dogs are good"

D. "Tell me dog stuff"

**17. What should you prioritize in prompt instructions?**

A. Using constraints over positive instructions

B. Using action verbs and positive instructions

C. Making prompts as long as possible

D. Using technical jargon

**18. How should you handle output formatting in prompts?**

A. Let the AI decide the format

B. Specify exactly how you want the response structured

C. Always use plain text

D. Avoid mentioning format requirements

**19. What is a key principle for reusable prompts?**

A. Make them as specific as possible

B. Use variables for reusability

C. Keep them very short

D. Avoid examples

**20. Why is iteration important in prompt engineering?**

A. It's not important

B. To improve performance through testing and refinement

C. To increase prompt length

D. To reduce costs

**21. What should you do with successful prompts?**

A. Keep them secret

B. Document them for future use

C. Delete them after use

D. Share them publicly immediately

**22. How should you handle contradictory instructions in prompts?**

A. Include as many constraints as possible

B. Review prompts for internal consistency

C. Let the AI figure it out

D. Use multiple prompts simultaneously

**23. What's the problem with too many constraints?**

A. They improve performance

B. Over-constraining limits model creativity

C. They reduce costs

D. They increase speed

**24. How should you approach token limits?**

A. Ignore them completely

B. Set appropriate limits and structure accordingly

C. Always use maximum tokens

D. Use minimum tokens always

**25. What's a common mistake in prompt testing?**

A. Testing too much

B. Assuming first attempt is optimal

C. Using different models

D. Testing with examples

## Advanced Concepts (26-50)

**26. What is contextual prompting?**

A. Using context from previous conversations

B. Providing specific background information relevant to the task

C. Removing all context

D. Using only system prompts

**27. In MoE models, what determines which experts are activated?**

A. Random selection

B. The gating network analyzes input and routes to relevant experts

C. User preferences

D. Computational availability

**28. How does MoE change prompt engineering?**

A. It doesn't change anything

B. It makes expert-aware prompting more important

C. It eliminates the need for prompts

D. It only affects system prompts

**29. What is prompt chaining?**

A. Connecting multiple AI models

B. Breaking complex tasks into sequential steps

C. Using chains to secure prompts

D. Linking prompts with special characters

**30. How should you handle multi-modal prompting?**

A. Use only text instructions

B. Be explicit about what to look for in images and combine text with visual instructions

C. Ignore visual elements

D. Use separate models for each modality

**31. What is the key to effective structured outputs?**

A. Using plain text only

B. Using JSON, XML, or other structured formats with clear schemas

C. Avoiding any structure

D. Using only bullet points

**32. How should you manage context in long conversations?**

A. Include everything from the beginning

B. Summarize previous context and use system messages effectively

C. Start fresh each time

D. Ignore previous context

**33. What makes a good testing framework for prompts?**

A. Random testing only

B. Documenting prompts systematically with version control and evaluation metrics

C. Testing once and moving on

D. Using the same test every time

**34. What are the key evaluation metrics for prompts?**

A. Speed only

B. Accuracy, relevance, completeness, style, and format adherence

C. Length only

D. Cost only

**35. How should you approach A/B testing with prompts?**

A. Test only one variation

B. Try different wordings, examples, settings, and output formats

C. Use identical prompts

D. Test only temperature settings


**36. What is mixture-of-experts (MoE) in AI models?**

A. A training technique

B. An architecture that uses specialized sub-networks with sparse activation

C. A type of database

D. A prompt engineering method

**37. How many experts might a typical MoE model have per layer?**

A. Always 2

B. Often dozens or hundreds (e.g., 8 in Mixtral 8x7B)

C. Always 1000+D

D. Never more than 3

**38. What percentage of parameters are typically activated in MoE models?**

A. 100%

B. Often 10-20% (sparse activation)

C. Always 50%

D. Less than 1%

**39. What is the gating network in MoE?**

A. A security feature

B. A lightweight mechanism that decides which experts to route data to

C. A storage system

D. A user interface component

**40. Why do MoE models require "load balancing" during training?**

A. To distribute network traffic

B. To prevent any single expert from being overused

C. To balance computational costs

D. To manage memory usage

**41. What is a key advantage of MoE architecture?**

A. Uses more memory

B. Achieves high performance with lower compute costs compared to dense models

C. Requires more training time

D. Works only with small datasets

**42. What is expert scaling in MoE?**

A. Making experts larger

B. Adding more experts increases capacity without proportional compute growth

C. Reducing expert size

D. Using fewer experts over time

**43. Which models are known to use MoE architecture?**

A. Only GPT models

B. Mixtral, Grok-1, Switch Transformers

C. Only image generation models

D. None of the major models

**44. What is a challenge with MoE routing?**

A. It's too predictable

B. Routing can be unstable and lead to load imbalances

C. It's too simple

D. It uses too little memory

**45. How does MoE affect prompt sensitivity?**

A. Reduces sensitivity

B. Amplifies prompt sensitivity because small changes can affect expert routing

C. Has no effect

D. Only affects system prompts

**46. What should you front-load in MoE prompts?**

A. Examples only

B. Domain signals and task cues to help router select right experts

C. Lengthy explanations

D. Multiple languages

**47. How should you handle mixed tasks in MoE models?**

A. Combine everything in one prompt

B. Separate mixed tasks or break into sequential steps

C. Use only simple tasks

D. Avoid mixed tasks entirely

**48. What vocabulary works best with MoE routing?**

A. Creative and indirect language

B. Unambiguous, domain-specific vocabulary

C. Technical jargon only

D. Poetic language

**49. How should examples be chosen for MoE few-shot prompting?**

A. Use diverse, unrelated examples

B. Match examples to the same domain, format, and language as the goal

C. Use only one example

D. Avoid examples completely

**50. What temperature settings help with MoE consistency?**

A. High temperature increases consistency

B. Lower temperature reduces expert churn and improves consistency

C. Temperature has no effect on MoE

D. Always use maximum temperature

## Practical Applications (51-75)

**51. For content creation prompts, what should you specify?**

A. Just the topic

B. Context, audience, tone, format, and specific requirements

C. Only the word count

D. Just the deadline

**52. How should you structure data analysis prompts?**

A. Ask general questions only

B. Provide clear analysis framework with specific output requirements

C. Use only yes/no questions

D. Avoid structure completely

**53. For code generation prompts, what elements are essential?**

A. Just the programming language

B. Requirements, error handling, documentation, examples, and type hints

C. Only the function name

D. Just the expected output

**54. What makes a good role prompt?**

A. Generic roles only

B. Specific expertise that matches the task (e.g., "experienced software architect")

C. Always use "assistant"

D. Avoid roles completely

**55. How should you handle technical documentation prompts?**

A. Keep them vague

B. Specify audience level, format, and include examples of desired output

C. Use only bullet points

D. Avoid technical terms

**56. What's important for translation prompts?**

A. Just specify source and target languages

B. Include context, tone, audience, and cultural considerations

C. Use machine translation first

D. Avoid examples

**57. For summarization tasks, what should you specify?**

A. Just ask for a summary

B. Specify length, key points to focus on, and target audience

C. Always use bullet points

D. Make summaries as long as possible

**58. How should you approach creative writing prompts?**

A. Be very restrictive

B. Provide genre, style, length, and key elements while allowing creativity

C. Give no guidance

D. Use only factual prompts

**59. What's crucial for classification prompts?**

A. Use many categories

B. Provide clear categories and examples for each class

C. Use only two categories

D. Avoid examples

**60. For question-answering systems, what should you include?**

A. Just the questions

B. Context, source materials, format for answers, and confidence indicators

C. Only multiple choice options

D. Random information

**61. How should you structure comparison prompts?**

A. List items randomly

B. Specify comparison criteria, format (table/prose), and depth of analysis

C. Compare everything to everything

D. Use only two items


**62. What's important in explanation prompts?**

A. Use complex language

B. Specify audience level, examples needed, and depth of explanation

C. Assume expert knowledge

D. Avoid analogies

**63. For brainstorming prompts, how should you balance structure and creativity?**

A. Be completely rigid

B. Provide enough structure to guide thinking while allowing creative exploration

C. Give no structure at all

D. Use only logical approaches

**64. What should problem-solving prompts include?**

A. Just the problem statement

B. Context, constraints, desired solution format, and success criteria

C. Only the final answer format

D. Multiple unrelated problems

**65. How should you approach research synthesis prompts?**

A. Ask for everything about the topic

B. Specify sources, synthesis framework, key themes, and output structure

C. Use only one source

D. Avoid citing sources

**66. What's essential for recommendation prompts?**

A. Generic recommendations

B. User context, criteria for recommendations, and reasoning for choices

C. Only popular options

D. Random suggestions

**67. For educational content prompts, what should you consider?**

A. One learning style only

B. Learning level, objectives, examples, and assessment methods

C. Advanced concepts only

D. No structure needed

**68. How should you structure email writing prompts?**

A. Just mention it's an email

B. Specify purpose, audience, tone, key points, and desired action

C. Use the same template always

D. Keep them very formal

**69. What's important for report writing prompts?**

A. Just the topic

B. Scope, audience, structure, data sources, and executive summary requirements

C. Only conclusions

D. Make them as long as possible

**70. For product description prompts, what should you include?**

A. Just basic features

B. Target audience, key benefits, tone, format, and competitive differentiators

C. Only technical specifications

D. Generic descriptions

**71. How should you approach social media prompts?**

A. Use the same approach for all platforms

B. Specify platform, audience, tone, length limits, and engagement goals

C. Ignore platform differences

D. Use only formal language

**72. What's crucial for customer service prompts?**

A. Always say yes to everything

B. Brand voice, escalation procedures, empathy guidelines, and solution focus

C. Use rigid scripts only

D. Avoid personalization

**73. For interview question prompts, what should you specify?**

A. Just the job title

B. Role level, skills to assess, question types, and evaluation criteria

C. Only generic questions

D. Use the same questions for all roles

**74. How should you structure meeting summary prompts?**

A. Include everything mentioned

B. Specify key decisions, action items, attendees, and next steps format

C. Only include complaints

D. Use chronological order only

**75. What's important for proposal writing prompts?**

A. Just the basic idea

B. Requirements, audience, structure, value proposition, and success metrics

C. Only the budget

D. Make them very long

## Troubleshooting and Optimization (76-90)

**76. If you get inconsistent answers across runs, what should you do?**

A. Ignore the inconsistency

B. Add sharper domain anchors and reduce temperature

C. Increase temperature

D. Use longer prompts

**77. What should you do if the AI misses the skill you want?**

A. Give up and try a different task

B. Use explicit skill tags and show target format in examples

C. Make the prompt longer

D. Use higher temperature

**78. How should you handle mixed-topic responses?**

A. Accept them as they are

B. Split the request or ask for a plan first, then execute steps

C. Use more complex prompts

D. Combine more topics

**79. What indicates a prompt needs refinement?**

A. It works perfectly every time

B. Inconsistent outputs, missing requirements, or wrong format

C. It's too short

D. It uses simple language

**80. How should you approach prompt optimization?**

A. Change everything at once

B. Make systematic changes and test variations methodically

C. Use random modifications

D. Copy others' prompts exactly

**81. What's a sign of over-prompting?**

A. Getting good results

B. Contradictory instructions or unnecessarily complex requirements

C. Short responses

D. Fast responses

**82. How should you handle prompt length concerns?**

A. Always use maximum length

B. Balance detail with conciseness, focus on essential elements

C. Always use minimum length

D. Length doesn't matter

**83. What should you do when a prompt works well for some cases but not others?**

A. Use it as-is

B. Analyze the failing cases and adjust for edge cases

C. Abandon the prompt

D. Use it only for successful cases

**84. How should you handle domain-specific terminology in prompts?**

A. Avoid it completely

B. Use it appropriately for the audience and provide definitions when needed

C. Use only technical terms

D. Use only common terms

**85. What's important when scaling prompts for production?**

A. Never change them

B. Monitor performance, handle edge cases, and maintain consistency

C. Make them more complex

D. Use different prompts for each user

**86. How should you handle cultural sensitivity in global prompts?**

A. Ignore cultural differences

B. Consider cultural context and avoid assumptions

C. Use only Western references

D. Make prompts culture-specific

**87. What should you do if responses are too verbose?**

A. Accept lengthy responses

B. Add specific length constraints and format requirements

C. Use higher temperature

D. Remove all constraints

**88. How should you handle ambiguous prompts?**

A. Let the AI interpret freely

B. Add clarifying details and specific examples

C. Make them more ambiguous

D. Use multiple interpretations

**89. What's important for maintaining prompt quality over time?**

A. Never update them

B. Regular testing, monitoring performance, and iterative improvements

C. Change them constantly

D. Use community feedback only

**90. How should you approach prompt versioning?**

A. Don't track versions

B. Document changes, reasons, and performance impacts systematically

C. Use only the latest version

D. Keep all versions active simultaneously

## Future and Advanced Topics (91-100)

**91. What's emerging in prompt engineering for 2025?**

A. Abandoning structured outputs

B. Multi-modal prompting, better context management, and MoE-aware techniques

C. Using only simple prompts

D. Eliminating examples

**92. How will prompt engineering evolve with more advanced AI?**

A. Become unnecessary

B. Require more sophisticated techniques for complex reasoning and tool use

C. Stay exactly the same

D. Become completely automated

**93. What's important for prompt engineering in conversational AI?**

A. Treating each turn independently

B. Context management, memory, and maintaining consistency across turns

C. Using only short responses

D. Avoiding previous context

**94. How should you approach prompt engineering for AI agents?**

A. Use the same techniques as chatbots

B. Focus on tool use instructions, task decomposition, and state management

C. Avoid giving agents any instructions

D. Use only simple commands

**95. What's the relationship between prompt engineering and fine-tuning?**

A. They're mutually exclusive

B. Prompt engineering can reduce the need for fine-tuning in many cases

C. Fine-tuning always replaces prompt engineering

D. They have no relationship

**96. How should you prepare for working with future AI models?**

A. Stop learning new techniques

B. Focus on fundamental principles while staying updated on model-specific features

C. Only learn current model techniques

D. Avoid systematic approaches

**97. What's important for prompt engineering in specialized domains?**

A. Use generic approaches only

B. Understand domain-specific requirements and terminology

C. Avoid domain expertise

D. Use the same prompts for all domains

**98. How should you approach collaborative prompt engineering?**

A. Work in isolation

B. Share knowledge, document best practices, and learn from others

C. Keep techniques secret

D. Use only individual approaches

**99. What's the role of evaluation in advanced prompt engineering?**

A. It's unnecessary

B. Systematic evaluation and metrics are crucial for optimization

C. Only manual evaluation matters

D. Evaluation slows down development


**100. What's the most important skill for future prompt engineers?**

A. Memorizing specific techniques

B. Systematic thinking, experimentation, and adaptation to new models

C. Using only proven methods

D. Avoiding complexity

---

## Answer Key

1. B  2. B  3. B  4. C  5. B  6. B  7. B  8. B  9. B  10. B

11. B  12. B  13. B  14. B  15. B  16. B  17. B  18.  B  19. B   20. B

21. B  22. B  23. B  24. B  25. B  26. B  27. B  28. B  29. B  30. B

31. B  32. B  33. B  34. B  35. B  36. B  37. B  38. B  39. B  40. B

41. B  42. B  43. B  44. B  45. B  46. B  47. B  48. B  49. B  50. B

51. B  52. B  53. B  54. B  55. B  56. B  57. B  58. B  59. B  60. B

61. B  62. B  63. B  64. B  65. B  66. B  67. B  68. B  69. B  70. B

71. B  72. B  73. B  74. B  75. B  76. B  77. B  78. B  79. B  80. B

81. B  82. B  83. B  84. B  85. B  86. B  87. B  88. B  89. B  90. B

91. B  92. B  93. B  94. B  95. B  96. B  97. B  98. B  99. B  100. B
