# Changelog

## [0.0.1](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/compare/v0.6.2...v0.0.1) (2026-05-12)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1426)) ([94e1295](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/94e129599d9799b65f8aa68833254040544bfdaa))
* add retry connection to ollama ([#2084](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2084)) ([fc2869d](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/fc2869d07cf8d08614b2eeaaee99ba4b64e2f658))
* Add stream information to generate SDKs ([#1569](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1569)) ([231e414](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/231e414538a6c8fce10c8e965d15d442cc7dffd5))
* Adding MistralAI mode ([#2065](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2065)) ([619c0ac](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/619c0acefbf11104276342d3527e44a3eba94ec0))
* **API:** Ingest plain text ([#1417](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1417)) ([c79282d](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c79282de16e2abed53f8cebeeb6b8e185db14d53))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1432)) ([75fce94](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/75fce94b74f0f6c4e7f496afbdfde21b8bbf5efe))
* bump dependencies ([#1987](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1987)) ([2ec2991](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/2ec299194810c34104cec0db38260d58048b7003))
* **code:** improve concat of strings in ui ([#1785](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1785)) ([6058743](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/605874326aa56d3eb2e1ef91d454555e541cbe50))
* Disable Gradio Analytics ([#1165](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1165)) ([d060220](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d060220bf14f57da02991c97878e120c285b2c9f))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1812)) ([1536009](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/153600953667789dddcdd98753032b51c798a707))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1782)) ([5abb77a](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/5abb77ab6cc3a59620fb64dd6caafa29b663b9d7))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1924)) ([6e5e5fe](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/6e5e5fee400f3af42890af9526efb3e6954f089f))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1741)) ([14a3bd8](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/14a3bd8dc560f6c04d906c83d8efce2f6e9c1593))
* **docs:** Fix setup docu ([#1926](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1926)) ([1eb4f41](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/1eb4f41d263afb083342927edd6f6cf14d5be33c))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1968)) ([71219fa](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/71219fa74ad63ad8fd361a9381595869e503a3cd))
* **docs:** update documentation and fix preview-docs ([#2000](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2000)) ([24042e6](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/24042e65e8fbf4fa6e6f7c82f6097cbe39fa09ab))
* **docs:** upgrade fern ([#1596](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1596)) ([e5a75aa](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/e5a75aad1f632257db32f024f592a6a91177a3e6))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1133)) ([fa0e437](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/fa0e437d95f9bf9080f687b9f0c81dccea04985c))
* enable resume download for hf_hub_download ([#1249](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1249)) ([ca369ab](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/ca369ab44cf8c253a3cc131f139685432adccd57))
* Get answers using preferred number of chunks ([188bcfd](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/188bcfdcee26ec26032ab1f956193ba488283ed4))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1750)) ([ac89a3e](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/ac89a3e7de2fe77fc2261dd573b6cd070e8734d9))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1698)) ([5adc6a7](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/5adc6a7d51580c0277ca13bce72cc3206db1fa99))
* **llm:** Add openailike llm mode ([#1447](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1447)) ([5b6beed](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/5b6beed6e9c4f5b9ebba41fac82b451c6618353a)), closes [#1424](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1424)
* **llm:** add progress bar when ollama is pulling models ([#2031](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2031)) ([3427f19](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/3427f19b48cd229f7cbb8f09955182446897cfb3))
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1526)) ([c921faf](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c921faf6056d29c592dd1cc8c36bb19651d35705))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1703)) ([03494dc](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/03494dc693a30a4ec09ca2fce6572f4bf752cf0f))
* **llm:** autopull ollama models ([#2019](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2019)) ([654375c](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/654375cc9d0cb1284b570d246503288b38781617))
* **llm:** drop default_system_prompt ([#1385](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1385)) ([76df2dd](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/76df2dd8b04b36426a41a248d6b26b763a1581cf))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1800)) ([277639e](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/277639ec19edc5e065206bef2bbe5ceb45d3d74a))
* **llm:** Ollama timeout setting ([#1773](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1773)) ([d2d3c4f](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d2d3c4f963275a6693ca3f1a9e3ef9133245b9ae))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1965)) ([9847279](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/9847279ba8eebab2958367b2c50fd436ed058cd3))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1467)) ([cf0f1f1](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/cf0f1f1b920de4ff168e9ce0a2dbff1bcf894f2b))
* make llama3.1 as default ([#2022](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2022)) ([436c453](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/436c4537a61688d54f164f1df443904ce8d4eb38))
* move torch and transformers to local group ([#1172](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1172)) ([f8b92cd](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f8b92cda4f1cced1edab2fb622d0549749b38339))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1706)) ([d7873a6](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d7873a6bfe6f890f40d37ae660abb824173da5bd))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1835)) ([a9c555a](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/a9c555a7068d894658c2c69deaccf2a3a4522e8c))
* Qdrant support ([#1228](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1228)) ([30680d1](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/30680d1698d5697ccac7ac5a645086c064b869ac))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1771)) ([f6172cc](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f6172cc2696397c6831fc49b461585b2fcb0badb))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1810)) ([ae9dff8](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/ae9dff8f6b7e320088e95197001fa01011da1723))
* **recipe:** add our first recipe  `Summarize` ([#2028](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2028)) ([849df49](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/849df499b944cefad34ced9ae953c7b2547ca07d))
* Release GitHub action ([#1078](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1078)) ([45578f8](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/45578f8d019cb719b133084793f5ef2a9ec60b21))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1783)) ([8f2af14](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/8f2af148032861a637b57347428967abd8487c18))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1437)) ([ce2aba3](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/ce2aba32c54afa640f6e257794a87f0d88d90e92))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1415)) ([c47eb77](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c47eb775790ce90542726e30a28be01ff249c50b))
* **ui:** add LLM mode to UI ([#1080](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1080)) ([0ff6dd4](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/0ff6dd4716d0b35437e24a2ff6980d565e8be238))
* **ui:** Add Model Information to ChatInterface label ([36096a1](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/36096a1601878a6f3b96509e30bbdaf7bf088dea))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1705)) ([354886a](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/354886a5fc230fbef2cfaa94f392bcc791d8fa4b))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1353)) ([e5c94f0](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/e5c94f0974de09248dffd79360e1f6db828fedb2))
* **UI:** Faster startup and document listing ([#1763](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1763)) ([cd11448](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/cd11448001ce8df9983cc03d50ba76dc43c34d84))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1643)) ([02816e7](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/02816e736b27736631d707c09776645f33ae4725))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1397)) ([44fbde5](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/44fbde5e2f145124660a292a572353b292a805c7))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1612)) ([a6b44ff](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/a6b44ffcfcc9a1007cf0b4d17c29bd7879ed9fee))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1730)) ([f12b155](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f12b15569efbacf7a05b2f86762db3f7b28af82a))
* update llama-index + dependencies ([#2092](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2092)) ([8d4492b](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/8d4492ba93f7d361582a3af278353be40e498a33))
* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1663)) ([af8fae2](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/af8fae2ebc2d7cf9c44b12271189a2809179a006))
* **vectordb:** Milvus vector db Integration ([#1996](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1996)) ([c4e9eb7](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c4e9eb7959aafabfc6fbae0053c513cb196d5fd1))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1883)) ([2ff05bf](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/2ff05bf4341c6e88bb244138c6a37134df8240b7))
* **Vector:** support pgvector ([#1624](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1624)) ([43d6f97](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/43d6f97b6335836c76f0b229b7d3f64e241d313a))
* wipe per storage type ([#1772](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1772)) ([8e8ef5d](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/8e8ef5ddd3a47139405ef31114ea3ba63e6a8dfc))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1841)) ([157fb46](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/157fb464cc9b803fc0e54949c749ea66374042c8))
* 294 (tested) ([668e121](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/668e121873406185c425776930de8ab47c51e7a6))
* 503 when private gpt gets ollama service ([#2104](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2104)) ([a817d27](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/a817d270fd45d69ec895f008a939a8a80d9a0a0a))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([ed00859](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/ed00859113914435c172660679d29cf98ec8e88e))
* add built image from DockerHub ([#2042](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2042)) ([7edf858](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/7edf858056e4381f4d8073a371f6ff3e946ea8fb))
* Add default mode option to settings ([#2078](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2078)) ([6bc2192](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/6bc21921a73cc13bf2aa48be9fc250cc11044866))
* add numpy issue to troubleshooting ([#2048](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2048)) ([c790c09](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c790c09d09f8cb1fab03e2318a46ba730c86bde1))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1519)) ([d42dbdb](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d42dbdbe339647a2247470cf12c43c26b4fac18c))
* Adding azopenai to model list ([#2035](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2035)) ([c857062](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c85706226ed40348300fb18bc5e5da0ee8998247))
* auto-update version ([#2052](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2052)) ([9765ea1](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/9765ea16f2cc597463b984a2316eca86029c2131))
* chromadb max batch size ([#1087](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1087)) ([c3661a3](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c3661a318722c2890efcd0ae5cec6fe8c5fb9dd1))
* **config:** make tokenizer optional and include a troubleshooting doc ([#1998](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1998)) ([7aacff2](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/7aacff2fe038923858c8e26e906d53333cc33ddc))
* **deploy:** fix local and external dockerfiles ([837f78b](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/837f78b483c55b29607f2787c21ab3ec9e8b56d7))
* **deploy:** generate docker release when new version is released ([#2038](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2038)) ([1671fa7](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/1671fa7c5b3cf40caaf9fa632aca0b5412a89a8d))
* **deploy:** improve Docker-Compose and quickstart on Docker ([#2037](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2037)) ([c2b92ac](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c2b92ac950f1fdb0afe67279c7a2041f0cd9ced6))
* Disable Chroma Telemetry ([3de7ec7](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/3de7ec7dc740ce03ca94cb775199e06714673014))
* Docker and sagemaker setup ([#1118](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1118)) ([223a5b4](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/223a5b402e4c1000f65734d158a88a9477e8b7f6))
* docker permissions ([#2059](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2059)) ([c82db14](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c82db14298c493555ceaff77e31b25d22a57ab2d))
* **docker:** docker broken copy ([#1419](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1419)) ([aa73703](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/aa73703f5ee7ee7fdad15bc8b178ea8a8371af32))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1779)) ([549130b](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/549130be04c4cd416d3c57765155ad3d1916ad89))
* **docs:** Minor documentation amendment ([#1739](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1739)) ([d60aaca](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d60aaca0dac312ee1e27dcde18a6139774924216))
* **docs:** Update installation.mdx ([#1866](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1866)) ([19a98da](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/19a98dae438d057d1a3aa7874216cdf4c23fd15d))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([e39f628](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/e39f6281a63bec5bf8e2b1323af7737edc79c735))
* ffmpy dependency ([#2020](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2020)) ([f268056](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f2680562dc89023ddd00c0528a002108f5ed3ec9))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1123)) ([cd40b76](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/cd40b76ce50f31a8553ebbb3b4d1305fa0080cb5))
* Fixed docker-compose ([#1758](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1758)) ([16b30ca](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/16b30ca2b74764a746cd235f655f9da2cf606b8c))
* **ingest:** update script label ([#1770](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1770)) ([9849491](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/9849491bd8718f8f8dbe25c242d627dba9b71a90))
* light mode ([#2025](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2025)) ([5775856](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/577585670d60ed35dca5896dd099d4c55e7089c8))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1954)) ([2b9e0a5](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/2b9e0a5904a0e86cb69c656ae89bbba1f03e471d))
* **llm:** special tokens and leading space ([#1831](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1831)) ([1cc37bd](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/1cc37bd6cb5bd508ddcc991456df71eff83dfa8e))
* make docs more visible ([#1081](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1081)) ([941c21a](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/941c21a3653f3c2c334312d899372346acaa3a7d))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1859)) ([f050904](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f050904a91baa64ccd1ad0d4b5675218402350e2))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1449)) ([f043d59](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f043d59c64308e2c93e1be76c9a47d1dda3d706a))
* naming image and ollama-cpu ([#2056](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2056)) ([e8df203](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/e8df20333d62cc476ae4b60b5ae189590605df21))
* nomic embeddings ([#2030](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2030)) ([86a4ea0](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/86a4ea0db08b276214cbfb124b4bc40f3f9a9453))
* prevent to ingest local files (by default) ([#2010](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2010)) ([c113758](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/c113758d0c442ac5d250373f5f48e6c3bdc9f3c8))
* publish image name ([#2043](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2043)) ([5dbeaba](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/5dbeabaf10f709e80e66c02e17c57ce0756a7178))
* Rectify ffmpy poetry config; update version from 0.3.2 to 0.4.0 ([#2062](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2062)) ([3caa617](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/3caa617aeb2833eb37670770ddcf8e8c500b7651))
* Remove global state ([#1216](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1216)) ([ca15db9](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/ca15db9d2283f0780fd76cf641349f4b209cc64e))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1890)) ([b20f422](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/b20f422c56f322f2791d0c687d48e2ab7d51b7d1))
* sagemaker config and chat methods ([#1142](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1142)) ([f7c3f5f](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f7c3f5f256f8ac02ec8c57f569672b8a35775808))
* Sanitize null bytes before ingestion ([#2090](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2090)) ([f5a486b](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f5a486b9254adbc7c176b7e85d9f9663c02f4d8a))
* **settings:** correct yaml multiline string ([#1403](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1403)) ([d795364](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d7953649126d5417961a8eb0a985ad4f865982e8))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1925)) ([dcbf0e7](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/dcbf0e7281dfccab8d320552bfbe00467f0f475a))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1709)) ([72360f6](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/72360f6a4c7b533f71061a0508f0e9eb035ed589))
* **tests:** load the test settings only when running tests ([0342b61](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/0342b61c5b44739d52dbd0db2eebbb4138506b5e))
* typo in README.md ([#1091](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1091)) ([8d52c91](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/8d52c914dd2dd630d9c5532596c6ea1bbd92a6dd))
* **ui:** gradio bug fixes ([#2021](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2021)) ([f191565](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/f191565b11f08676b414bcf35cede75f31f3daf3))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([2bed5d0](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/2bed5d0c701ecfd5aa1b7bbd502add5b9a2dad71))
* unify embedding models ([#2027](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/2027)) ([885f700](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/885f7007374828bce596045517754b5695567a78))
* update matplotlib to 3.9.1-post1 to fix win install ([9e77c6b](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/9e77c6bbd311c78a7fd384e7354b239114f25d0e))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1260)) ([48f1a3c](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/48f1a3c3cfdf92ada358f43347cec840b837ef8f))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/issues/1280)) ([d222649](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d222649f799ff46c15aae1ec2083dd03b123f2b8))


### Miscellaneous Chores

* Initial version ([d51ea78](https://github.com/benjaminwilsonmgs-cell/privatestack-ai/commit/d51ea787374372e7d0573c9afdb84533b5422108))

## [0.6.2](https://github.com/zylon-ai/private-gpt/compare/v0.6.1...v0.6.2) (2024-08-08)


### Bug Fixes

* add numpy issue to troubleshooting ([#2048](https://github.com/zylon-ai/private-gpt/issues/2048)) ([4ca6d0c](https://github.com/zylon-ai/private-gpt/commit/4ca6d0cb556be7a598f7d3e3b00d2a29214ee1e8))
* auto-update version ([#2052](https://github.com/zylon-ai/private-gpt/issues/2052)) ([7fefe40](https://github.com/zylon-ai/private-gpt/commit/7fefe408b4267684c6e3c1a43c5dc2b73ec61fe4))
* publish image name ([#2043](https://github.com/zylon-ai/private-gpt/issues/2043)) ([b1acf9d](https://github.com/zylon-ai/private-gpt/commit/b1acf9dc2cbca2047cd0087f13254ff5cda6e570))
* update matplotlib to 3.9.1-post1 to fix win install ([b16abbe](https://github.com/zylon-ai/private-gpt/commit/b16abbefe49527ac038d235659854b98345d5387))

## [0.6.1](https://github.com/zylon-ai/private-gpt/compare/v0.6.0...v0.6.1) (2024-08-05)


### Bug Fixes

* add built image from DockerHub ([#2042](https://github.com/zylon-ai/private-gpt/issues/2042)) ([f09f6dd](https://github.com/zylon-ai/private-gpt/commit/f09f6dd2553077d4566dbe6b48a450e05c2f049e))
* Adding azopenai to model list ([#2035](https://github.com/zylon-ai/private-gpt/issues/2035)) ([1c665f7](https://github.com/zylon-ai/private-gpt/commit/1c665f7900658144f62814b51f6e3434a6d7377f))
* **deploy:** generate docker release when new version is released ([#2038](https://github.com/zylon-ai/private-gpt/issues/2038)) ([1d4c14d](https://github.com/zylon-ai/private-gpt/commit/1d4c14d7a3c383c874b323d934be01afbaca899e))
* **deploy:** improve Docker-Compose and quickstart on Docker ([#2037](https://github.com/zylon-ai/private-gpt/issues/2037)) ([dae0727](https://github.com/zylon-ai/private-gpt/commit/dae0727a1b4abd35d2b0851fe30e0a4ed67e0fbb))

## [0.6.0](https://github.com/zylon-ai/private-gpt/compare/v0.5.0...v0.6.0) (2024-08-02)


### Features

* bump dependencies ([#1987](https://github.com/zylon-ai/private-gpt/issues/1987)) ([b687dc8](https://github.com/zylon-ai/private-gpt/commit/b687dc852413404c52d26dcb94536351a63b169d))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/zylon-ai/private-gpt/issues/1924)) ([d13029a](https://github.com/zylon-ai/private-gpt/commit/d13029a046f6e19e8ee65bef3acd96365c738df2))
* **docs:** Fix setup docu ([#1926](https://github.com/zylon-ai/private-gpt/issues/1926)) ([067a5f1](https://github.com/zylon-ai/private-gpt/commit/067a5f144ca6e605c99d7dbe9ca7d8207ac8808d))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/zylon-ai/private-gpt/issues/1968)) ([19a7c06](https://github.com/zylon-ai/private-gpt/commit/19a7c065ef7f42b37f289dd28ac945f7afc0e73a))
* **docs:** update documentation and fix preview-docs ([#2000](https://github.com/zylon-ai/private-gpt/issues/2000)) ([4523a30](https://github.com/zylon-ai/private-gpt/commit/4523a30c8f004aac7a7ae224671e2c45ec0cb973))
* **llm:** add progress bar when ollama is pulling models ([#2031](https://github.com/zylon-ai/private-gpt/issues/2031)) ([cf61bf7](https://github.com/zylon-ai/private-gpt/commit/cf61bf780f8d122e4057d002abf03563bb45614a))
* **llm:** autopull ollama models ([#2019](https://github.com/zylon-ai/private-gpt/issues/2019)) ([20bad17](https://github.com/zylon-ai/private-gpt/commit/20bad17c9857809158e689e9671402136c1e3d84))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/zylon-ai/private-gpt/issues/1965)) ([fc13368](https://github.com/zylon-ai/private-gpt/commit/fc13368bc72d1f4c27644677431420ed77731c03))
* make llama3.1 as default ([#2022](https://github.com/zylon-ai/private-gpt/issues/2022)) ([9027d69](https://github.com/zylon-ai/private-gpt/commit/9027d695c11fbb01e62424b855665de71d513417))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/zylon-ai/private-gpt/issues/1835)) ([e21bf20](https://github.com/zylon-ai/private-gpt/commit/e21bf20c10938b24711d9f2c765997f44d7e02a9))
* **recipe:** add our first recipe  `Summarize` ([#2028](https://github.com/zylon-ai/private-gpt/issues/2028)) ([8119842](https://github.com/zylon-ai/private-gpt/commit/8119842ae6f1f5ecfaf42b06fa0d1ffec675def4))
* **vectordb:** Milvus vector db Integration ([#1996](https://github.com/zylon-ai/private-gpt/issues/1996)) ([43cc31f](https://github.com/zylon-ai/private-gpt/commit/43cc31f74015f8d8fcbf7a8ea7d7d9ecc66cf8c9))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/zylon-ai/private-gpt/issues/1883)) ([2612928](https://github.com/zylon-ai/private-gpt/commit/26129288394c7483e6fc0496a11dc35679528cc1))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/zylon-ai/private-gpt/issues/1841)) ([947e737](https://github.com/zylon-ai/private-gpt/commit/947e737f300adf621d2261d527192f36f3387f8e))
* **config:** make tokenizer optional and include a troubleshooting doc ([#1998](https://github.com/zylon-ai/private-gpt/issues/1998)) ([01b7ccd](https://github.com/zylon-ai/private-gpt/commit/01b7ccd0648be032846647c9a184925d3682f612))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/zylon-ai/private-gpt/issues/1779)) ([dde0224](https://github.com/zylon-ai/private-gpt/commit/dde02245bcd51a7ede7b6789c82ae217cac53d92))
* **docs:** Update installation.mdx ([#1866](https://github.com/zylon-ai/private-gpt/issues/1866)) ([c1802e7](https://github.com/zylon-ai/private-gpt/commit/c1802e7cf0e56a2603213ec3b6a4af8fadb8a17a))
* ffmpy dependency ([#2020](https://github.com/zylon-ai/private-gpt/issues/2020)) ([dabf556](https://github.com/zylon-ai/private-gpt/commit/dabf556dae9cb00fe0262270e5138d982585682e))
* light mode ([#2025](https://github.com/zylon-ai/private-gpt/issues/2025)) ([1020cd5](https://github.com/zylon-ai/private-gpt/commit/1020cd53288af71a17882781f392512568f1b846))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/zylon-ai/private-gpt/issues/1954)) ([c7212ac](https://github.com/zylon-ai/private-gpt/commit/c7212ac7cc891f9e3c713cc206ae9807c5dfdeb6))
* **llm:** special tokens and leading space ([#1831](https://github.com/zylon-ai/private-gpt/issues/1831)) ([347be64](https://github.com/zylon-ai/private-gpt/commit/347be643f7929c56382a77c3f45f0867605e0e0a))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/zylon-ai/private-gpt/issues/1859)) ([2a432bf](https://github.com/zylon-ai/private-gpt/commit/2a432bf9c5582a94eb4052b1e80cabdb118d298e))
* nomic embeddings ([#2030](https://github.com/zylon-ai/private-gpt/issues/2030)) ([5465958](https://github.com/zylon-ai/private-gpt/commit/54659588b5b109a3dd17cca835e275240464d275))
* prevent to ingest local files (by default) ([#2010](https://github.com/zylon-ai/private-gpt/issues/2010)) ([e54a8fe](https://github.com/zylon-ai/private-gpt/commit/e54a8fe0433252808d0a60f6a08a43c9f5a42f3b))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/zylon-ai/private-gpt/issues/1890)) ([9d0d614](https://github.com/zylon-ai/private-gpt/commit/9d0d614706581a8bfa57db45f62f84ab23d26f15))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/zylon-ai/private-gpt/issues/1925)) ([966af47](https://github.com/zylon-ai/private-gpt/commit/966af4771dbe5cf3fdf554b5fdf8f732407859c4))
* **ui:** gradio bug fixes ([#2021](https://github.com/zylon-ai/private-gpt/issues/2021)) ([d4375d0](https://github.com/zylon-ai/private-gpt/commit/d4375d078f18ba53562fd71651159f997fff865f))
* unify embedding models ([#2027](https://github.com/zylon-ai/private-gpt/issues/2027)) ([40638a1](https://github.com/zylon-ai/private-gpt/commit/40638a18a5713d60fec8fe52796dcce66d88258c))

## [0.5.0](https://github.com/zylon-ai/private-gpt/compare/v0.4.0...v0.5.0) (2024-04-02)


### Features

* **code:** improve concat of strings in ui ([#1785](https://github.com/zylon-ai/private-gpt/issues/1785)) ([bac818a](https://github.com/zylon-ai/private-gpt/commit/bac818add51b104cda925b8f1f7b51448e935ca1))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/zylon-ai/private-gpt/issues/1812)) ([f83abff](https://github.com/zylon-ai/private-gpt/commit/f83abff8bc955a6952c92cc7bcb8985fcec93afa))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/zylon-ai/private-gpt/issues/1782)) ([8a836e4](https://github.com/zylon-ai/private-gpt/commit/8a836e4651543f099c59e2bf497ab8c55a7cd2e5))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/zylon-ai/private-gpt/issues/1741)) ([5725181](https://github.com/zylon-ai/private-gpt/commit/572518143ac46532382db70bed6f73b5082302c1))
* **docs:** upgrade fern ([#1596](https://github.com/zylon-ai/private-gpt/issues/1596)) ([84ad16a](https://github.com/zylon-ai/private-gpt/commit/84ad16af80191597a953248ce66e963180e8ddec))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/zylon-ai/private-gpt/issues/1750)) ([134fc54](https://github.com/zylon-ai/private-gpt/commit/134fc54d7d636be91680dc531f5cbe2c5892ac56))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/zylon-ai/private-gpt/issues/1698)) ([1efac6a](https://github.com/zylon-ai/private-gpt/commit/1efac6a3fe19e4d62325e2c2915cd84ea277f04f))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/zylon-ai/private-gpt/issues/1703)) ([02dc83e](https://github.com/zylon-ai/private-gpt/commit/02dc83e8e9f7ada181ff813f25051bbdff7b7c6b))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/zylon-ai/private-gpt/issues/1800)) ([b3b0140](https://github.com/zylon-ai/private-gpt/commit/b3b0140e244e7a313bfaf4ef10eb0f7e4192710e))
* **llm:** Ollama timeout setting ([#1773](https://github.com/zylon-ai/private-gpt/issues/1773)) ([6f6c785](https://github.com/zylon-ai/private-gpt/commit/6f6c785dac2bbad37d0b67fda215784298514d39))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/zylon-ai/private-gpt/issues/1467)) ([821bca3](https://github.com/zylon-ai/private-gpt/commit/821bca32e9ee7c909fd6488445ff6a04463bf91b))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/zylon-ai/private-gpt/issues/1706)) ([68b3a34](https://github.com/zylon-ai/private-gpt/commit/68b3a34b032a08ca073a687d2058f926032495b3))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/zylon-ai/private-gpt/issues/1771)) ([087cb0b](https://github.com/zylon-ai/private-gpt/commit/087cb0b7b74c3eb80f4f60b47b3a021c81272ae1))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/zylon-ai/private-gpt/issues/1810)) ([83adc12](https://github.com/zylon-ai/private-gpt/commit/83adc12a8ef0fa0c13a0dec084fa596445fc9075))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/zylon-ai/private-gpt/issues/1783)) ([ea153fb](https://github.com/zylon-ai/private-gpt/commit/ea153fb92f1f61f64c0d04fff0048d4d00b6f8d0))
* **ui:** Add Model Information to ChatInterface label ([f0b174c](https://github.com/zylon-ai/private-gpt/commit/f0b174c097c2d5e52deae8ef88de30a0d9013a38))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/zylon-ai/private-gpt/issues/1705)) ([290b9fb](https://github.com/zylon-ai/private-gpt/commit/290b9fb084632216300e89bdadbfeb0380724b12))
* **UI:** Faster startup and document listing ([#1763](https://github.com/zylon-ai/private-gpt/issues/1763)) ([348df78](https://github.com/zylon-ai/private-gpt/commit/348df781b51606b2f9810bcd46f850e54192fd16))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/zylon-ai/private-gpt/issues/1643)) ([410bf7a](https://github.com/zylon-ai/private-gpt/commit/410bf7a71f17e77c4aec723ab80c233b53765964))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/zylon-ai/private-gpt/issues/1730)) ([63de7e4](https://github.com/zylon-ai/private-gpt/commit/63de7e4930ac90dd87620225112a22ffcbbb31ee))
* wipe per storage type ([#1772](https://github.com/zylon-ai/private-gpt/issues/1772)) ([c2d6948](https://github.com/zylon-ai/private-gpt/commit/c2d694852b4696834962a42fde047b728722ad74))


### Bug Fixes

* **docs:** Minor documentation amendment ([#1739](https://github.com/zylon-ai/private-gpt/issues/1739)) ([258d02d](https://github.com/zylon-ai/private-gpt/commit/258d02d87c5cb81d6c3a6f06aa69339b670dffa9))
* Fixed docker-compose ([#1758](https://github.com/zylon-ai/private-gpt/issues/1758)) ([774e256](https://github.com/zylon-ai/private-gpt/commit/774e2560520dc31146561d09a2eb464c68593871))
* **ingest:** update script label ([#1770](https://github.com/zylon-ai/private-gpt/issues/1770)) ([7d2de5c](https://github.com/zylon-ai/private-gpt/commit/7d2de5c96fd42e339b26269b3155791311ef1d08))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/zylon-ai/private-gpt/issues/1709)) ([d17c34e](https://github.com/zylon-ai/private-gpt/commit/d17c34e81a84518086b93605b15032e2482377f7))

## [0.4.0](https://github.com/imartinez/privateGPT/compare/v0.3.0...v0.4.0) (2024-03-06)


### Features

* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/imartinez/privateGPT/issues/1663)) ([45f0571](https://github.com/imartinez/privateGPT/commit/45f05711eb71ffccdedb26f37e680ced55795d44))
* **Vector:** support pgvector ([#1624](https://github.com/imartinez/privateGPT/issues/1624)) ([cd40e39](https://github.com/imartinez/privateGPT/commit/cd40e3982b780b548b9eea6438c759f1c22743a8))

## [0.3.0](https://github.com/imartinez/privateGPT/compare/v0.2.0...v0.3.0) (2024-02-16)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/imartinez/privateGPT/issues/1426)) ([e326126](https://github.com/imartinez/privateGPT/commit/e326126d0d4cd7e46a79f080c442c86f6dd4d24b))
* Add stream information to generate SDKs ([#1569](https://github.com/imartinez/privateGPT/issues/1569)) ([24fae66](https://github.com/imartinez/privateGPT/commit/24fae660e6913aac6b52745fb2c2fe128ba2eb79))
* **API:** Ingest plain text ([#1417](https://github.com/imartinez/privateGPT/issues/1417)) ([6eeb95e](https://github.com/imartinez/privateGPT/commit/6eeb95ec7f17a618aaa47f5034ee5bccae02b667))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/imartinez/privateGPT/issues/1432)) ([b178b51](https://github.com/imartinez/privateGPT/commit/b178b514519550e355baf0f4f3f6beb73dca7df2))
* **llm:** Add openailike llm mode ([#1447](https://github.com/imartinez/privateGPT/issues/1447)) ([2d27a9f](https://github.com/imartinez/privateGPT/commit/2d27a9f956d672cb1fe715cf0acdd35c37f378a5)), closes [#1424](https://github.com/imartinez/privateGPT/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/imartinez/privateGPT/issues/1526)) ([6bbec79](https://github.com/imartinez/privateGPT/commit/6bbec79583b7f28d9bea4b39c099ebef149db843))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/imartinez/privateGPT/issues/1437)) ([4780540](https://github.com/imartinez/privateGPT/commit/47805408703c23f0fd5cab52338142c1886b450b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/imartinez/privateGPT/issues/1415)) ([8ec7cf4](https://github.com/imartinez/privateGPT/commit/8ec7cf49f40701a4f2156c48eb2fad9fe6220629))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/imartinez/privateGPT/issues/1397)) ([c71ae7c](https://github.com/imartinez/privateGPT/commit/c71ae7cee92463bbc5ea9c434eab9f99166e1363))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/imartinez/privateGPT/issues/1612)) ([aa13afd](https://github.com/imartinez/privateGPT/commit/aa13afde07122f2ddda3942f630e5cadc7e4e1ee))


### Bug Fixes

* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/imartinez/privateGPT/issues/1519)) ([869233f](https://github.com/imartinez/privateGPT/commit/869233f0e4f03dc23e5fae43cf7cb55350afdee9))
* **deploy:** fix local and external dockerfiles ([fde2b94](https://github.com/imartinez/privateGPT/commit/fde2b942bc03688701ed563be6d7d597c75e4e4e))
* **docker:** docker broken copy ([#1419](https://github.com/imartinez/privateGPT/issues/1419)) ([059f358](https://github.com/imartinez/privateGPT/commit/059f35840adbc3fb93d847d6decf6da32d08670c))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([0a89d76](https://github.com/imartinez/privateGPT/commit/0a89d76cc5ed4371ffe8068858f23dfbb5e8cc37))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/imartinez/privateGPT/issues/1449)) ([6191bcd](https://github.com/imartinez/privateGPT/commit/6191bcdbd6e92b6f4d5995967dc196c9348c5954))
* **settings:** correct yaml multiline string ([#1403](https://github.com/imartinez/privateGPT/issues/1403)) ([2564f8d](https://github.com/imartinez/privateGPT/commit/2564f8d2bb8c4332a6a0ab6d722a2ac15006b85f))
* **tests:** load the test settings only when running tests ([d3acd85](https://github.com/imartinez/privateGPT/commit/d3acd85fe34030f8cfd7daf50b30c534087bdf2b))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([24fb80c](https://github.com/imartinez/privateGPT/commit/24fb80ca38f21910fe4fd81505d14960e9ed4faa))

## [0.2.0](https://github.com/imartinez/privateGPT/compare/v0.1.0...v0.2.0) (2023-12-10)


### Features

* **llm:** drop default_system_prompt ([#1385](https://github.com/imartinez/privateGPT/issues/1385)) ([a3ed14c](https://github.com/imartinez/privateGPT/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/imartinez/privateGPT/issues/1353)) ([145f3ec](https://github.com/imartinez/privateGPT/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))

## [0.1.0](https://github.com/imartinez/privateGPT/compare/v0.0.2...v0.1.0) (2023-11-30)


### Features

* Disable Gradio Analytics ([#1165](https://github.com/imartinez/privateGPT/issues/1165)) ([6583dc8](https://github.com/imartinez/privateGPT/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/imartinez/privateGPT/issues/1133)) ([64c5ae2](https://github.com/imartinez/privateGPT/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/imartinez/privateGPT/issues/1249)) ([4197ada](https://github.com/imartinez/privateGPT/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* move torch and transformers to local group ([#1172](https://github.com/imartinez/privateGPT/issues/1172)) ([0d677e1](https://github.com/imartinez/privateGPT/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/imartinez/privateGPT/issues/1228)) ([03d1ae6](https://github.com/imartinez/privateGPT/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))


### Bug Fixes

* Docker and sagemaker setup ([#1118](https://github.com/imartinez/privateGPT/issues/1118)) ([895588b](https://github.com/imartinez/privateGPT/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/imartinez/privateGPT/issues/1123)) ([24cfddd](https://github.com/imartinez/privateGPT/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* Remove global state ([#1216](https://github.com/imartinez/privateGPT/issues/1216)) ([022bd71](https://github.com/imartinez/privateGPT/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/imartinez/privateGPT/issues/1142)) ([a517a58](https://github.com/imartinez/privateGPT/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* typo in README.md ([#1091](https://github.com/imartinez/privateGPT/issues/1091)) ([ba23443](https://github.com/imartinez/privateGPT/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/imartinez/privateGPT/issues/1260)) ([0d52002](https://github.com/imartinez/privateGPT/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/imartinez/privateGPT/issues/1280)) ([f1cbff0](https://github.com/imartinez/privateGPT/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))

## [0.0.2](https://github.com/imartinez/privateGPT/compare/v0.0.1...v0.0.2) (2023-10-20)


### Bug Fixes

* chromadb max batch size ([#1087](https://github.com/imartinez/privateGPT/issues/1087)) ([f5a9bf4](https://github.com/imartinez/privateGPT/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))

## 0.0.1 (2023-10-20)

### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/imartinez/privateGPT/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))
