# Backend

## API Routes

Route | Datastructure
--- | ---
/ | {}
/queues.json | {<br/>&emsp;"queues": [<br/>&emsp;&emsp;{<br/>&emsp;&emsp;&emsp;"count": 0,<br/>&emsp;&emsp;&emsp;"name": "queue-name",<br/>&emsp;&emsp;&emsp;"url": "/queue-name"<br/>&emsp;&emsp;}<br/>&emsp;]<br/>}
/workers.json | {<br/>&emsp;"workers": [<br/>&emsp;&emsp;{<br/>&emsp;&emsp;&emsp;"current_job": "idle",<br/>&emsp;&emsp;&emsp;"name": "6f0418be8c2e4df49a5c13c4bc89ee21",<br/>&emsp;&emsp;&emsp;"python_version": "3.8.8 (default, Feb 19 2021, 18:07:06) \n[GCC 8.3.0]",<br/>&emsp;&emsp;&emsp;"queues": [<br/>&emsp;&emsp;&emsp;&emsp;"queue-name"<br/>&emsp;&emsp;&emsp;],<br/>&emsp;&emsp;&emsp;"state": "idle",<br/>&emsp;&emsp;&emsp;"version": "1.7.0"<br/>&emsp;&emsp;}<br/>&emsp;]<br/>}
/jobs | {<br/>&emsp;"jobs": [],<br/>&emsp;"name": "",<br/>&emsp;"pagination": {}<br/>}

# Frontend

# pip

# Docker

