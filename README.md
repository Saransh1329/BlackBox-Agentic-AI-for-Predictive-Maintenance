# BlackBox-Agentic-AI-for-Predictive-Maintenance
What This Project Does

The system analyzes maintenance and fault history to:

Predict failure probability

Estimate Remaining Useful Life (RUL)

Detect recurring fault patterns

Generate Root Cause Analysis (RCA)

Recommend Corrective and Preventive Actions (CAPA)

Output everything in a structured Excel report

Once you run it, you don’t get charts to interpret.
You get answers.

Why This Matters

Most predictive maintenance tools stop at “this might fail.”

This one answers:

Why is it failing?

How urgent is it?

What action should be taken now?

What should be changed to prevent it permanently?

That’s the difference between analytics and decision-making.

Project Structure

The system is organized as a pipeline of notebooks, each with a clear role:

File	Purpose
ai1.ipynb	Data loading, cleaning, and normalization
ai2.ipynb	Feature engineering and health indicators
ai3.ipynb	Failure probability and RUL estimation
ai4.ipynb	Fleet-level pattern and recurrence detection
ai5.ipynb	Agentic reasoning for RCA and CAPA
ai6.ipynb	Full pipeline execution and Excel report generation

Each notebook builds on the previous one.

Key Outputs

The system generates a single Excel file containing:

Asset / vehicle ID

Fault description and category

Failure probability (%)

Remaining Useful Life (hours)

Priority score

Root Cause Analysis (text)

Corrective actions

Preventive actions

Recommended timeline

Manufacturing and design feedback

Estimated maintenance cost
