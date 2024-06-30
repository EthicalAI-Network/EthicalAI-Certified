EthicalAI Certified™ is an open-source initiative employing large language models (LLMs) to generate an ethical benchmark score for AI models and systems. It aims to safeguard, distinguish, and enhance the acceptance of products with AI applications. The resultant certification and marker highlight an organization's commitment towards delivering more reliable AI experiences for their users.

Through instructional support, evaluation, and independent corroboration, EthicalAI Certified™ provides the capability to amplify responsible innovation applications, improving the quality of AI use, bolstering trust among key stakeholders, and realizing corresponding advantages.

#### Guidance and Assessment

Certified EthicalAI Assessors provide instrumental support to organizations, conducting a detailed examination of their AI models and systems. The objective is to outline the ethical risks and benefits profile and determine compliance with relevant ethical standards.

#### Independent Audit and Confirmation

Following a comprehensive and independent audit of the assessment by an EthicalAI Certified verifier, a certificate and marker are awarded, confirming the ethical integrity of the AI models and systems used within the organization.

---
library_name: peft
---
## Training procedure


The following `bitsandbytes` quantization config was used during training:
- load_in_8bit: False
- load_in_4bit: True
- llm_int8_threshold: 6.0
- llm_int8_skip_modules: None
- llm_int8_enable_fp32_cpu_offload: False
- llm_int8_has_fp16_weight: False
- bnb_4bit_quant_type: nf4
- bnb_4bit_use_double_quant: False
- bnb_4bit_compute_dtype: float16
### Framework versions


- PEFT 0.4.0
