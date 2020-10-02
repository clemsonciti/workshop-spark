---
title: Setup
---

> ## Prerequisites
> You must have an active Palmetto account. To register
> for a Palmetto account, visit [New Account Request page](https://www.palmetto.clemson.edu/palmetto/basic/new/). 
>
{: .callout}

> ## Step 1. Open JupyterHub
> 
> - Open a browser and go to [https://www.palmetto.clemson.edu](https://www.palmetto.clemson.edu).
> - Click the JupyterHub link
>
> <img src="../fig/setup/01.png" alt="JupyterHub page" style="height:400px">
>
{: .slide}


> ## Step 2. Start My Server
> 
> - Click the blue `Start My Server` button
>
> <img src="../fig/setup/02.png" alt="Start My Server" style="height:400px">
>
{: .slide}


> ## Step 3. Server Options
> 
> - Select the options as shown in the screenshot below
>   - Check the `Advanced` box to show the additional options.
>
> <img src="../fig/setup/03.png" alt="Server Options" style="height:1000px">
>
{: .slide}


> ## Step 4. Getting Workshop Materials
> 
> - Select `File`/`New`/`Terminal`
>
> <img src="../fig/setup/04.png" alt="Terminal" style="height:300px">
>
> - Run the following commands in the terminal
>
> ~~~
> $ cp -R /zfs/citi/spark/myspark .
> $ cd myspark
> $ ls -l
> ~~~
> {: .language-bash}
>
> <img src="../fig/setup/05.png" alt="get myspark" style="height:350px">
{: .slide}


{% include links.md %}
