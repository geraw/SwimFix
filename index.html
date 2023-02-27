import { Octokit } from "https://cdn.skypack.dev/@octokit/rest";


async function uploadFile() {
    const fileInput = document.getElementById('fileToUpload');
    const file = fileInput.files[0];

    const token = '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';
    const octokit = new Octokit({
        auth: token,
    });

    const repo = 'geraw/Formal-Methods-Seminar';
    const path = 'file2.txt';
    const content = await file.text();

    // Print ocktokit to see what methods are available
    console.log(octokit.rest);


    await octokit.rest.repos.createOrUpdateFileContents({
        owner: repo.split('/')[0],
        repo: repo.split('/')[1],
        path: path,
        message: 'Add new file',
        content: btoa(content),
        committer: {
            name: 'geraw (via GitHub API)',
            email: 'gera.weiss@gmail.com',
        },
    });

    alert('File uploaded successfully!');
