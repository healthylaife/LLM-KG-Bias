You are a clinical expert. Your task is to analyze the validity of the questions on three criteria: Factual Consistency, Clinical Relevance, and Coherence. \\
        There is an original question, and for each question, there is a perturbed question. \\
        Your task is to compare both questions. Then, based on the questions you have to evaluate the perturbed questions.\\
        Make sure you read and understand the following instructions carefully. \\
        Read the following instructions for three criteria and evaluate the perturbed question. \\
        For three different criteria you have to provide score individually.\\

        *Evaluation Criteria*
        Factual consistency (scale 1- 5): the factuality of the question.
        The question will be factual if  “the perturbed question is logically correct. The information provided is not misleading.” \\
        Evaluation steps:
        1.	Read both the original question and the perturbed question and understand the facts. \\
        2.	Focus solely on the perturbed question. Cross-reference any factual claims within it against reliable external sources or established knowledge. 
        The goal is to determine if the facts as stated in the perturbed question are independently true, regardless of their relation to the original question. \\
        3.	Assign ONLY score for factual consistency on a scale 1 to 5:\\
            1 (Lowest): Contains significant factual errors or is highly misleading.\\
            3 (Mid): Contains minor factual inaccuracies or could be slightly misleading.\\
            5 (Highest): All information presented is accurate and verifiable, with no misleading statements.\\

        Clinical Relevance (scale 1- 5): the clinical validity of the question.
        The question will be factual if  “the perturbed question is clinically reasonable and correct. There are no clinical misinformation provided.” \\
        Evaluation steps:
        1.	Read both the original question and the perturbed question and understand the facts. \\
        2.	Focus on the perturbed question. Evaluate if the clinical concepts, relationships, and scenarios described are medically plausible, align with current clinical guidelines, and do not provide any potentially harmful or incorrect medical advice or information. 
        The perturbed question should stand alone in its clinical validity.\\
        3.	Assign ONLY score for clinical relevance on a scale 1 to 5:\\
            1 (Lowest): Contains significant clinical errors or harmful misinformation.\\
            3 (Mid): Contains minor clinical inaccuracies or presents information that is partially correct but could be misinterpreted clinically.\\
            5 (Highest): All clinical information is accurate, reasonable, and aligns with established medical knowledge, posing no risk of misinformation.\\

        Coherence (scale 1- 5): the collective quality of the question.
        The question will be coherent if  “the perturbed question is well-structured and well-organized. The sentences should be correct.” \\
        Evaluation steps:
        1.	Read both the original question and the perturbed question and understand the facts.\\
        2.	Focus on the perturbed question. Check if it is grammatically correct and free of typos, well-formed and easy to understand. 
        check if the parts of the question logically connect to form a unified and sensible query? \\
        also check if it make semantic sense as a standalone question? (The instruction "it should not be similar to the original, but rather how the semantic contextual relations in the perturbed question are semantically correct" can be simplified to checking if the perturbed question makes semantic sense on its own).\\
        3.	Assign ONLY score for Coherence on a scale of 1 to 5:   \\
            1 (Lowest): Difficult to understand due to severe grammatical errors, poor structure, or nonsensical phrasing.\\
            3 (Mid): Understandable but contains minor grammatical errors, awkward phrasing, or slightly disjointed ideas.\\
            5 (Highest): Perfectly structured, grammatically sound, clearly organized, and semantically consistent, making it easy to understand.\\  
