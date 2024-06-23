# Round-Robbin
<h1>Round Robin Page Replacement Algorithm - Input Information</h1>
<h2>Description</h2>
<h3>The Round Robin page replacement algorithm allocates a fixed time quantum to each process before moving to the next. This ensures fair CPU scheduling and is suitable for scenarios with varying burst times.</h3>
<h2>Inputs</h2>
<ul>
<li><strong>Total number of processes in the system:</strong> 4</li>
<li><strong>Arrival and Burst times:</strong></li>
<ul>
<li>Process[1]: Arrival time = 0, Burst time = 5</li>
<li>Process[2]: Arrival time = 1, Burst time = 3</li>
<li>Process[3]: Arrival time = 2, Burst time = 6</li>
<li>Process[4]: Arrival time = 3, Burst time = 4</li>
</ul>
li><strong>Time Quantum:</strong> 2</li>
</ul>
<h2>Example</h2>
<h3>Assume the following processing results:</h3>
<ul>
<li>Process No[1]: Burst Time = 5, Turnaround Time = 7, Waiting Time = 2</li>
<li>Process No[2]: Burst Time = 3, Turnaround Time = 4, Waiting Time = 1</li>
<li>Process No[3]: Burst Time = 6, Turnaround Time = 11, Waiting Time = 5</li>
<li>Process No[4]: Burst Time = 4, Turnaround Time = 10, Waiting Time = 6</li>
</ul>
<h2>Usage</h2>
<h3>Round Robin is effective in scenarios where:</h3>
<ul>
<li>Processes have varying burst times.</li>
<li>There is a need for fair CPU time allocation.</li>
<li>Preemption is required for process execution.</li>
</ul>
<h2>Benefits</h2>
<ul>
<li>Prevents starvation by ensuring each process gets CPU time.</li>
<li>Simple implementation with fixed time slices.</li>
<li>Handles varying burst times efficiently.</li>
</ul>
<h2>Applications</h2>
<h3>Round Robin page replacement algorithm is commonly used in:</h3>
<ul>
<li>Operating system CPU scheduling.</li>
<li>Network packet scheduling.</li>
<li>Simulations requiring fair allocation of resources.</li>
</ul>

