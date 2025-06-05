

## EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

## Aim:
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 
        ChatGPT (GPT-4)

## **Algorithm**  

### **1. Define the Two Prompt Types**  
| **Prompt Type** | **Characteristics** | **Example** |  
|----------------|-------------------|------------|  
| **Naïve Prompt** | Broad, vague, lacks specificity | *"Tell me about diabetes."* |  
| **Basic Prompt** | Clear, structured, provides context | *"Explain type 2 diabetes, its causes, symptoms, and management in 100 words."* |  

### **2. Select Test Scenarios**  
Five scenarios were chosen:  
1. **Creative Story Writing**  
2. **Factual Question Answering**  
3. **Article/Concept Summarization**  
4. **Advice/Recommendation**  
5. **Technical Explanation**  

### **3. Run Experiments**  
- For each scenario, **naïve and basic prompts** were tested.  
- ChatGPT’s responses were recorded and compared.  

### **4. Evaluation Metrics**  
- **Quality** (Clarity, coherence, engagement)  
- **Accuracy** (Factual correctness)  
- **Depth** (Detail, relevance, usefulness)  

---

## **Results & Comparative Analysis**  

### **Scenario 1: Creative Story Writing**  
| **Prompt Type** | **Prompt** | **Response Analysis** |  
|----------------|-----------|----------------------|  
| **Naïve** | *"Write a story."* | Generic, lacks plot or characters. Output: *"Once upon a time, there was a hero who saved the day."* |  
| **Basic** | *"Write a 200-word sci-fi story about an AI discovering human emotions."* | Structured, engaging, follows prompt constraints. Output: Detailed narrative with emotional AI protagonist. |  

**Verdict:** Basic prompts yield **higher quality & depth**.  

---

### **Scenario 2: Factual Question Answering**  
| **Prompt Type** | **Prompt** | **Response Analysis** |  
|----------------|-----------|----------------------|  
| **Naïve** | *"What is hypertension?"* | Brief, lacks depth. Output: *"High blood pressure."* |  
| **Basic** | *"Explain hypertension, its causes, risks, and prevention in 150 words."* | Detailed, structured, medically accurate. |  

**Verdict:** Basic prompts improve **accuracy & depth**.  

---

### **Scenario 3: Article Summarization**  
| **Prompt Type** | **Prompt** | **Response Analysis** |  
|----------------|-----------|----------------------|  
| **Naïve** | *"Summarize this article."* (No article provided) | Fails—no input text. |  
| **Basic** | *"Summarize the key points of this 500-word article on blockchain in 3 bullet points."* | Concise, extracts main ideas effectively. |  

**Verdict:** Basic prompts **essential** for summarization.  

---

### **Scenario 4: Advice/Recommendation**  
| **Prompt Type** | **Prompt** | **Response Analysis** |  
|----------------|-----------|----------------------|  
| **Naïve** | *"Give me health tips."* | Generic advice (*"Eat well, exercise."*) |  
| **Basic** | *"Provide 5 evidence-based tips for managing arthritis pain in elderly patients."* | Specific, actionable, medically sound. |  

**Verdict:** Basic prompts ensure **higher relevance & usefulness**.  

---

### **Scenario 5: Technical Explanation**  
| **Prompt Type** | **Prompt** | **Response Analysis** |  
|----------------|-----------|----------------------|  
| **Naïve** | *"Explain machine learning."* | Surface-level definition. |  
| **Basic** | *"Compare supervised vs. unsupervised learning with real-world examples."* | Detailed, structured, practical examples. |  

**Verdict:** Basic prompts **enhance clarity & depth**.  

---

## **Key Findings**  

1. **Basic prompts consistently outperform naïve prompts** in:  
   - **Accuracy** (Fewer vague/incomplete answers)  
   - **Depth** (More detailed, structured responses)  
   - **Quality** (More engaging, relevant outputs)  

2. **Naïve prompts work acceptably only in very open-ended tasks** (e.g., brainstorming).  

3. **Best practices for optimal ChatGPT responses:**  
   - Provide **context & constraints** (word count, format).  
   - Specify **tone & audience** (e.g., "Explain to a beginner").  
   - Use **examples** in few-shot prompting.  

---

## **Deliverables Summary**  

### **Table: Naïve vs. Basic Prompt Comparison**  
| **Scenario** | **Naïve Prompt Performance** | **Basic Prompt Performance** |  
|-------------|----------------------------|----------------------------|  
| Creative Writing | Low depth, generic | High depth, engaging |  
| Factual QA | Brief, lacks detail | Accurate, structured |  
| Summarization | Fails without input | Effective with guidance |  
| Advice | Generic, less useful | Specific, actionable |  
| Technical Explanation | Surface-level | Detailed, examples included |  

### Result 
- **Basic prompts significantly improve ChatGPT’s output quality.**  
- **Naïve prompts should be avoided** for precise, structured tasks.  
- **Optimal prompting requires clarity, specificity, and constraints.**  

# RESULT: 
The prompt for the above said problem executed successfully
