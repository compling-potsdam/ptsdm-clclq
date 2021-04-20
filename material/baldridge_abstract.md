## Language, vision and action are better together

*Jason Baldridge, Google Research, Austin, TX, USA*

*April 28th, 2021*

### Abstract

Human knowledge and use of language is inextricably connected to
perception, action and the organization of the brain, yet
natural language processing is still dominated by text! More research
involving language---including speech---in the context of other modalities
and environments is needed, and there has never been a better time to do
it.

Without ever invoking the worn-out, overblown phrase "how babies learn" in
the talk, I'll cover three of my team's efforts
involving language, vision and action. First: our work on speech-image
representation learning and retrieval, where we demonstrate settings in
which directly encoding speech outperforms the hard-to-beat strategy of
using automatic speech recognition and strong text encoders. Second: two
models for text-to-image generation: a multi-stage model which exploits
user-guidance in the form of mouse traces and a single-stage one which uses
cross-modal contrastive losses. Third: Room-across-Room, a multilingual
dataset for vision-and-language navigation, for which we collected spoken
navigation instructions, high-quality text transcriptions, and fine-grained
alignments between words and pixels in high-definition 360-degree
panoramas. I'll wrap up with some thoughts on how work on
computational language grounding more broadly presents new opportunities to
enhance and advance our scientific understanding of language and its
fundamental role in human intelligence.

Relevant papers:

- Ramon Sanabria, Austin Waters, Jason Baldridge. Talk, Don't Write: A
Study of Direct Speech-Based Image Retrieval
<https://arxiv.org/pdf/2104.01894>. arxiv preprint
- Jing Yu Koh, Jason Baldridge, Honglak Lee, Yinfei Yang. Text-to-image
generation grounded by fine-grained user attention
<https://openaccess.thecvf.com/content/WACV2021/papers/Koh_Text-to-Image_Generation_Grounded_by_Fine-Grained_User_Attention_WACV_2021_paper.pdf>.
WACV 2021
- Han Zhang, Jing Yu Koh, Jason Baldridge, Honglak Lee, Yinfei Yang.Cross-Modal
Contrastive Learning for Text-to-Image Generation
<https://arxiv.org/pdf/2101.04702>. CVPR 2021
- Alexander Ku, Peter Anderson, Roma Patel, Eugene Ie, Jason Baldridge. Room-Across-Room: Multilingual Vision-and-Language Navigation with Dense Spatiotemporal Grounding <https://www.aclweb.org/anthology/2020.emnlp-main.356/>. EMNLP
2020
- James L McClelland, Felix Hill, Maja Rudolph, Jason Baldridge, Hinrich
Schütze. Placing language in an integrated understanding system: Next steps
toward human-level performance in neural language models
<https://web.stanford.edu/~jlmcc/papers/McCEtAl20PlacingLanguageInAnIntegratedUnderstandingSystem.pdf>.
PNAS 2020.
