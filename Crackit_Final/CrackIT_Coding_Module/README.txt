CrackIT Coding Module

Included:
- Updated crackit.html with Fullscreen Exam Mode and proctored exam UI.
- coding_dataset.js with 2,507 high-quality coding questions across 21 DSA topics.

Coding test behavior:
- Easy: 8 questions, 1 hour 30 minutes
- Medium: 5 questions, 1 hour 30 minutes
- Hard: 3 questions, 1 hour
- All Levels: 3 mixed questions, 1 hour
- Fullscreen Exam Mode:
  * Automatically enters browser fullscreen on 'Start Test'.
  * Hides sidebar, topbar, and background navigation during exam.
  * Detects fullscreen exit via fullscreenchange and displays a proctoring warning modal.
  * Warning options: 'Return to Fullscreen' or 'Submit Exam' (with confirmation dialog).
  * Auto-stops exit warnings once the exam is submitted or timer expires.
- 2,500+ curated questions covering Arrays, Strings, Searching, Sorting, Hashing, Two Pointers, Sliding Window, Stacks, Queues, Linked Lists, Trees, BST, Heaps, Dynamic Programming, Graphs, BFS/DFS, Backtracking, Greedy, Bit Manipulation, Matrices, and Math.
- Random selection with localStorage tracking to prevent question repetition.
- Each problem includes statement, input/output format, constraints, 2+ examples, and 5 test cases.
- 5 Programming languages supported: C, C++, Java, Python, and JavaScript.
- Dynamic editor starter comments for each language.
- Code execution via Judge0 CE API checking all test cases with detailed pass/fail & error reports.
- Manual 'Submit Test' and automatic submission when timer reaches zero.
- Complete performance analytics & breakdown upon test completion.

Important:
- Code execution requires an active internet connection (Judge0 CE API).
- For production deployment, configure your own Judge0 API endpoint/backend proxy.
