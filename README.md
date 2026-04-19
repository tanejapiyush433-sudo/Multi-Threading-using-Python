⚡ Parallel Matrix Multiplication using Multiprocessing

This project demonstrates parallel computing in Python using the multiprocessing module to perform large-scale matrix multiplications efficiently. It evaluates how increasing the number of worker processes impacts execution time and CPU utilization.

🚀 Overview

The program generates random matrices and multiplies them with a constant matrix using multiple processes. It runs experiments with 1 to 12 workers and records performance metrics to analyze scalability.

🧠 Key Concepts
Multiprocessing in Python
Parallel task execution
Performance benchmarking
CPU utilization analysis
Data visualization with graphs
⚙️ How It Works
A large constant matrix is generated once
Multiple random matrices are created per task
Each process performs matrix multiplication independently
Execution time and CPU usage are recorded
Results are visualized using graphs
📊 Output

The program generates two graphs:

Execution Time vs Workers → Shows how performance improves with more processes
CPU Usage vs Workers → Displays how system resources are utilized
🛠️ Technologies Used
Python 3
NumPy
Multiprocessing
Matplotlib
Psutil
▶️ How to Run
pip install numpy matplotlib psutil
python your_script_name.py
📈 Insights
Increasing workers reduces execution time initially
Performance gain stabilizes after optimal CPU utilization
Demonstrates limits of parallelism and system constraints
📌 Conclusion

This project highlights how multiprocessing can significantly improve performance for compute-intensive tasks like matrix multiplication, while also showcasing the importance of balancing resource usage.
