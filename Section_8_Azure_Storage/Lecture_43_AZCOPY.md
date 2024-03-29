# Lecture 43 AZCOPY

Hypothetical situation

1 or more containers with 100s of GB of data

We want to copy those files into another storage account in the same or different subscription

How?

I could download the data to my local computer and then upload it to the storage account.

Terrible b/c it has to deal with lots and lots of data. There is a data charge for bandwidth. Many TBs to bring to your computer

AZCOPY
* A solution to this is AZCOPY. command line tool.
* Could also go to/from your local PC.
* Good for between storage accounts without the local-between layer

https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10

![Alt text](image-24.png)

Get the file SAS

![Alt text](image-25.png)

Get the target container SAS

![Alt text](image-26.png)

Example:

Target File to copy

https://storagedemo2924.blob.core.windows.net/firstone/space1.png?sp=r&st=2024-02-09T17:56:35Z&se=2024-02-10T01:56:35Z&spr=https&sv=2022-11-02&sr=b&sig=86bp2wym5nRl9uvxLdi7jbXvLDaHNXWXFFQmpk%2B5kbg%3D

Target container to receive the blob

https://secondbeanz.blob.core.windows.net/secondcontainer?sp=racwdl&st=2024-02-09T17:52:32Z&se=2024-02-10T01:52:32Z&spr=https&sv=2022-11-02&sr=c&sig=2uo5EyBpSOR2lQ0CP5DsopWdgFk%2BrSSWaW0wIxBMZNw%3D

Go into cloud shell but we could download AZcopy locally.

Test if azcopy is enabled

![Alt text](image-27.png)

Command

```
azcopy copy '<source-file>' '<dest-container>'   
```

Example command:

```
azcopy copy 'https://storagedemo2924.blob.core.windows.net/firstone/space1.png?sp=r&st=2024-02-09T17:56:35Z&se=2024-02-10T01:56:35Z&spr=https&sv=2022-11-02&sr=b&sig=86bp2wym5nRl9uvxLdi7jbXvLDaHNXWXFFQmpk%2B5kbg%3D' 'https://secondbeanz.blob.core.windows.net/secondcontainer?sp=racwdl&st=2024-02-09T17:52:32Z&se=2024-02-10T01:52:32Z&spr=https&sv=2022-11-02&sr=c&sig=2uo5EyBpSOR2lQ0CP5DsopWdgFk%2BrSSWaW0wIxBMZNw%3D'   
```

Example run:

![Alt text](image-28.png)

And the file made it over:

![Alt text](image-29.png)
