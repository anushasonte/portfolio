---
title: "Buffer Manager for Page Operations"
description: "Associated with Illinois Institute of Technology"
dateString: Feb 2023 - Mar 2023
draft: false
tags: ["C", "Database"]
showToc: false
weight: 204
--- 

#### 🔗 [View Project](https://github.com/anushasonte/ADO/tree/main/BufferManager)

## Description
The buffer manager manages a fixed number of pages in memory that represent pages from a page file managed by the storage manager. The memory pages managed by the buffer manager are called page frames. We call the combination of a page file and the page frames storing pages from that file a Buffer Pool. The Buffer manager handles more than one open buffer pool at the same time. However, there will only be one buffer pool for each page file. Each buffer pool uses one page replacement strategy that is determined when the buffer pool is initialized. FIFO and LRU page replacement strategies have been implemented currently. 

The main functionalities include initializing buffer pool, force flushing buffer pool, shutting down buffer pool, marking a page dirty, pinning and unpinning the page and some static functions to return the buffer pool contents. 
