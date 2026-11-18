---
author:
 - Νεκταρία Ζευγουλά
author-genitive: Νεκταρίας Ζευγουλά
author-mnr: 1089133
subject: Διπλωματική
title: Υποστήριξη διδασκαλίας με ανάπτυξη Μεγάλων Γλωσσικών Μοντέλων
title-en: Teaching support using Large Language Models
date: Φεβρουάριος 2026
place: Πάτρα
school: Πολυτεχνική Σχολή
department: Ηλεκτρολόγων Μηχανικών και Τεχνολογίας Υπολογιστών
supervisor: Σιντόρης Χρήστος, Ε.ΔΙ.Π.
commitee:
    - Ξένος Μιχάλης, Καθηγητής
    - Κομνηνός Ανδρέας, Επίκουρος Καθηγητής
director: Δεν ξέρω
abstract-el: "Η παρούσα διπλωματική εργασία πραγματεύεται τη μελέτη, τον σχεδιασμό και την ανάπτυξη μιας διαδικτυακής εκπαιδευτικής πλατφόρμας, η οποία αξιοποιεί τις δυνατότητες των Μεγάλων Γλωσσικών Μοντέλων (LLMs) για να προσφέρει στοχευμένη υποστήριξη σε φοιτητές και διδάσκοντες. Η αναγκαιότητα του συστήματος εδράζεται πρωτίστως στην ανάγκη ενίσχυσης της ενεργητικής μάθησης μέσω τακτικών ερωτηματολογίων αυτοαξιολόγησης (quizzes), η χειροκίνητη σύνταξη των οποίων αποδεικνύεται εξαιρετικά χρονοβόρα για τους διδάσκοντες, ιδίως όταν απαιτείται συνδυασμός της προφορικής διδασκαλίας με το υλικό των διαφανειών. Δευτερευόντως, το σύστημα αντιμετωπίζει την τάση των φοιτητών να καταφεύγουν σε γενικά εργαλεία Τεχνητής Νοημοσύνης χωρίς ακαδημαϊκή τεκμηρίωση, γεγονός που υπονομεύει την ουσιαστική μελέτη και αυξάνει τον κίνδυνο αφομοίωσης λανθασμένων πληροφοριών (hallucinations).


Για την αντιμετώπιση αυτών των προκλήσεων, κεντρικό πυρήνα της πλατφόρμας αποτελεί ένας αυτοματοποιημένος, πολυτροπικός αγωγός (pipeline) παραγωγής ερωτηματολογίων. Μέσω αυτού, ο διδάσκων καταγράφει τη διάλεξή του, η οποία μετατρέπεται αυτόματα σε κείμενο μέσω απομαγνητοφώνησης (speech-to-text) και συγχωνεύεται με το εξαγόμενο κείμενο και τις περιγραφές των οπτικών στοιχείων των διαφανειών. Αξιοποιώντας αυτή την ενιαία βάση γνώσης, το σύστημα παράγει δυναμικά εξατομικευμένα quizzes —προσαρμοσμένα στις παραμέτρους του διδάσκοντα— συνοδευόμενα από επεξηγήσεις και παραπομπές στις πηγές του μαθήματος. Συμπληρωματικά, η πλατφόρμα ενσωματώνει ένα δευτερεύον υποσύστημα ερωταπαντήσεων (chatbot), το οποίο επιτρέπει στους φοιτητές να υποβάλλουν ερωτήματα με απαντήσεις βασισμένες αποκλειστικά στο εγκεκριμένο υλικό της διάλεξης, περιορίζοντας δραστικά τον κίνδυνο αυθαίρετων αποκρίσεων."

abstract-en: "This diploma thesis presents the study, design, and development of a web-based educational platform that leverages Large Language Models (LLMs) and speech-to-text processing to support university instruction and active learning. The platform primarily addresses the challenge of creating regular self-assessment quizzes—a proven pedagogical tool for knowledge retention that is often neglected due to instructors' heavy workloads and the fragmentation of lecture content across spoken narration and presentation slides. To solve this, the core of the system consists of an automated, multimodal quiz generation pipeline: instructors record their lectures, which are automatically transcribed via speech-to-text and fused with extracted text and visual element descriptions from presentation slides. Using this unified knowledge base, the pipeline dynamically generates customized quizzes tailored to instructor parameters, complete with answer explanations and source references. Secondarily, the platform incorporates a complementary Q&A chatbot for students, operating under strict context grounding to provide responses anchored exclusively to verified lecture materials, thereby minimizing hallucinations and preventing passive reliance on unverified AI outputs."

acknowlegements: Δεν ξέρω
keywords-el:
    -
keywords-en:
    -
lang: el-GR
book: true
toc-own-page: true
toc: true
classoption:
    - twoside
titlepage: true
colorlinks: true
indent: true
header-includes:
    # - |
    #     ```{=latex}
    #     \usepackage{awesomebox}
    #     ```
    - |
        ```{=latex}
        \usepackage{cleveref}
        % pandoc-fignos: change the caption name
        \renewcommand{\figurename}{Εικόνα}
        ```
# \usepackage{caption}

pandoc-latex-environment:
    noteblock: [note]
    tipblock: [tip]
    warningblock: [warning]
    cautionblock: [caution]
    importantblock: [important]
titlepage-text-color: 0A0A0A
logo: images/uplogo.png
logo-stamp: images/logo-up-4color-stamp.jpg
signature: images/student-signature.png
listings-disable-line-numbers: false
disable-header-and-footer: false
# header-center: header-center
header-left: "\\hspace{1cm}"
header-right: "\\rightmark"
first-chapter: 1
biblatex: true
bibliography: bibliography/bibliography.bib
reference-section-title: 'Βιβλιογραφία'
mainfont: "Linux Libertine O"
CJKmainfont: Noto Serif CJK SC
sansfont: "Linux Biolinum O"
monofont: "Ubuntu Mono"
lof: true # List of figures
lot: true # List of tables
# geometry: [a4paper, bindingoffset=0mm, inner=20mm, outer=20mm, top=20mm, bottom=20mm] # See https://ctan.org/pkg/geometry for more options
fignos-cleveref: False
fignos-plus-name: Εικόνα
fignos-star-name: Εικόνα
fignos-caption-name: Εικόνα
fignos-caption-separator: period
fignos-number-by-section: False
secnos-plus-name: Ενότητα
secnos-star-name: Ενότητα
caption-labelformat: original
---