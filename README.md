# cs8803-pr1-multithreading-solution
**TO GET THIS SOLUTION VISIT:** [cs8803 Pr1 Multithreading Solution](https://www.ankitcodinghub.com/product/cs8803-pr1-multithreading-solution/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89754&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;cs8803 Pr1 Multithreading Solution&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Foreword

In this project, you will design and implement a multi-threaded web server that serves static files based on a GetFile protocol. Alongside the server, you will also create a multi-threaded client that acts as a load generator for the server. Both the server and client will be written in C and be based on a sound, scalable design.

Setup

Please follow the instructions given in the file Installation.md to set-up the virtual environment.

Submission Instructions

All code should be submitted through the submit.py script given at the top level of this repository. For instructions on how to submit individual components of the assignment see the instructions below. You may submit as many times as you like. Your last submission before the project deadline will be downloaded by the teaching assistants and graded according to the assignment rubric.

After submitting, you may double-check the results of your submission by visiting the Udacity/GT autograding website and going to the student portal.

Note: under heavy load, you may get a timeout error from Bonnie. The results on the web page will show you the estimated completion time. When the test run is completed, your results will be updated.

Do not submit the job multiple times – this makes it go slower (since there are now more jobs to process,) not faster

README

Throughout the project, we encourage you to keep notes on what you have done, how you have approached each part of the project and what resources you used in preparing your work. We have provided you with a prototype file, readme-student.md that you should use throughout the project.

You may submit your readme-student.md file with the command

python submit.py readme

At the prompt, please provide your GT username and password. [] (TAs should specify –provider udacity and use their personal Udacity accounts.) The program will then ask you if you want to save the jwt. If you reply yes, it will save a token on your filesystem so that you don’t have to provide your username and password each time that you submit.

The Udacity site will store your readme-student.md file in a database. This will be used during grading. The submit script will acknowledge receipt of your README file.

For this and all assignments, you may submit your code as many times as you like. After the deadline, we download your last submission prior to the deadline, review your submission and assign a grade.*

Warm-up: Sockets

In this project, your client and server will communicate via sockets. To help you familiarize yourself with C’s standard socket API, you will complete a few warm-up exercises

Echo Client-Server

Most socket tutorials start with a client-server pair where the server simply echoes (that is, repeats back) the message that the client sends. Sometimes referred to as the EchoClient and the EchoServer. In the first part of this assignment, you will turn in a pair of programs that perform these roles.

For this first part of the assignment, we will make some simplifying assumptions. You may assume that neither the message to the server nor the response will be longer than 15 bytes. Thus, you may statically allocate memory (e.g. char buffer[16];) and then pass this memory address into send or recv. Because these messages are so short, you may assume that the full message is sent or received in every send or recv call. (If you may like, you may detect when this is not the case by looking at the return value and simply exiting if the full message is not sent or received). Neither your server nor your client should assume that the string response will be null-terminated, however.

Your client code should support the following command-line options.

usage:

echoclient [options]

options:

-s Server (Default: localhost)

-p Port (Default: 8140)

-m Message to send to server (Default: “hello world.”

-h Show this help message

Note that code needed to parse these command line options is provided for you in the starter code. Also, it is important that the only output (either to stdout or stderr) be the response from the server.

As for the server, its command line interface need only allow the port to be specified. Again, the starter code shows how to parse the command line options.

usage:

echoserver [options]

options:

-p Port (Default: 8140)

-m Maximum pending connections (default: 8)

-h Show this help message

Note that your echoserver should not terminate after sending its first response; rather, it should prepare to serve another request. You may consult the references suggested in this document or others on the internet.

Once you have completed your programs inside the echo directory, you may submit it with the command

python submit.py echo

At the prompt, please provide your GT username and password. The program will then ask you if you want to save the jwt. Reply, yes to have a token saved on your filesystem so that you don’t have to provide your username and password each time that you submit.

Bonnie will test your echoclient.c code with its own reference implementation of the echoserver.c and your echoserver.c code with its own reference implementation of echoclient.c. It will then return some feedback to help you refine your code.

For this and all assignments, you may submit your code as many times as you like. After the deadline, a grader download your last submission, assess your design and finally assigning a grade.*

Transferring a File

Because the network interface is a shared resource, the OS does not guarantee that calls to send will copy the contents of the full range of memory that is specified to the socket. Instead, (for non-blocking sockets) the OS may copy as much of the memory range as it can fit in the network buffer and then lets the caller know how much it copied via the return value.

For example, after

int socket;

char *buffer

size_t length;

ssize_t sent;

/* Preparing message */

…

/*Sending message */

sent = send(socket, buffer, length, 0);

assert( sent == length); //WRONG!

You should not assume that sent has the same value as length. The function send may need to be called again (with different parameters) to ensure that the full message is sent.

Similarly, for recv, for TCP sockets, the OS does not wait for the range of memory specified to be completely filled with data from the network before the call returns. Instead, only a portion of the originally sent data may be delivered from the network to the memory address specified in a recv operation. The OS will let the caller know how much data it wrote via the return value of the recv call.

In several ways, this behavior is desirable, not only from the perspective of the operating system which must ensure that resources are properly shared, but also from the user’s perspective. For instance, the user may have no need to store in memory all of the data to be transferred. If the goal is to simply save data received over the network to disk, then this can be done a chunk at a time without having to store the whole file in memory.

In fact, it is this strategy that you should employ as the second part of the warm-up. You are to create a client, which simply connects to a server–no message need be sent– and saves the received data to a file on disk.

Beware of file permissions. Make sure to give yourself read and write access, e.g. S_IRUSR | S_IWUSR as the last parameter to open.

Your client code should support the following command-line options.

usage:

transferclient [options]

options:

-s Server (Default: localhost)

-p Port (Default: 8140)

-o Output file (Default gios.txt)

-h Show this help message

A sender of data may also want to use this approach of sending it a chunk at a time to conserve memory. Employ this strategy as you create a server that simply begins transferring data from a file over the network once it establishes a connection and closes the socket when finished.

usage:

transferserver [options]

options:

-f Filename (Default: cs8803.txt)

-h Show this help message

-p Port (Default: 8140)

You may consult the references suggested in this document or others on the internet. Starter code is provided inside of the transfer directory. Once you have completed your programs inside this directory, you may submit it with the command

python submit.py transfer

Part 1: Implementing the Getfile Protocol

Getfile is a simple protocol used to transfer a file from one computer to another that we made up for this project. A typical successful transfer is illustrated below.

Getfile Transfer Figure

The general form of a request is

&lt;scheme&gt; &lt;method&gt; &lt;path&gt;rnrn

Note:

The scheme is always GETFILE.

The method is always GET (though there are rumors that HEAD will be added one day).

The path must always start with a ‘/’.

The general form of a response is

&lt;scheme&gt; &lt;status&gt; &lt;length&gt;rnrn&lt;content&gt;

Note:

The scheme is always GETFILE.

The status must be in the set {‘OK’, ‘FILE_NOT_FOUND’, ‘ERROR’}.

FILE_NOT_FOUND is the appropriate response whenever the client has made an error in his request. ERROR is reserved for when the server is responsible for something bad happening.

No content may be sent if the status is FILE_NOT_FOUND or ERROR.

When the status is OK, the length should be a number expressed in ASCII (what sprintf will give you). The length parameter should be omitted for statuses of FILE_NOT_FOUND or ERROR.

The sequence ‘rnrn’ marks the end of the header. All remaining bytes are the files contents.

The space between the &lt;scheme&gt; and the &lt;method&gt; and the space between the &lt;method&gt; and the &lt;path&gt; are required. The space between the &lt;path&gt; and ‘rnrn’ is optional.

The space between the &lt;scheme&gt; and the &lt;status&gt; and the space between the &lt;status&gt; and the &lt;length&gt; are required. The space between the &lt;length&gt; and ‘rnrn’ is optional.

Instructions

For Part 1 of the assignment you will implement a Getfile client library and a Getfile server library. The API and the descriptions of the individual functions can be found in the gfclient.h and gfserver.h header files. Your task is to implement these interfaces in the gfclient.c and gfserver.c files respectively. To help illustrate how the API is intended to be used and to help you test your code we have provided the other files necessary to build a simple Getfile server and workload generating client inside of the gflib directory. It contains the files

Makefile – (do not modify) used for compiling the project components

content.[ch] – (do not modify) a library that abstracts away the task of fetching content from disk.

content.txt – (modify to help test) a data file for the content library

gfclient.c – (modify and submit) implementation of the gfclient interface.

gfclient.h – (do not modify) header file for the gfclient library

gfclient_download.c – (modify to help test) the main file for the client workload generator. Illustrates use of gfclient library.

gfserver.c – (modify and submit) implementation of the gfserver interface.

gfserver.h – (do not modify) header file for the gfserver library.

gfserver_main.c (modify to help test) the main file for the Getfile server. Illustrates the use of the gfserver library.

handler.c – (modify to help test) contains the handler callback that is registered with the gfserver library.

workload.[ch] – (do not modify) a library used by workload generator

workload.txt – (modify to help test) a data file indicating what paths should be requested and where the results should be stored.

gfclient

The client-side interface documented in gfclient.h is inspired by libcurl’s “easy” interface. To help illustrate how the API is intended to be used and to help you test your code, we have provided the file gfclient_download.c. For those not familiar with function pointers in C and callbacks, the interface can be confusing. The key idea is that before the user tells the gfclient library to perform a request, he should register one function to be called on the header (gfc_set_headerfunc) and register one function to be called for every “chunk” of the body (gfc_set_writefunc). That is, one call to the latter function will be made for every recv() call made by the gfclient library. (It so happens that none of the test code actually will use the header function, but please implement your library to support it anyway.)

The user of the gfclient library may want his callback functions to have access to data besides the information about the request provided by the gfclient library. For example, the write callback may need to know the file to which it should write the data. Thus, the user can register an argument that should be passed to his callback on every call. He does this with the gfc_set_headerarg and gfc_set_writearg functions. (Note that the user may have multiple requests being performed at once so a global variable is not suitable here.)

Note that the gfcrequest_t is used as an opaque pointer, meaning that it should be defined within the gfclient.c file and no user code (e.g. gfclient_download.c) should ever do anything with the object besides pass it to functions in the gfclient library.

gfserver

The server side interface documented in gfserver.h is inspired by python’s built-in httpserver. The existing code in the files handler.c and gfserver_main.c illustrate this usage. Again, for those not familiar with function pointers in C and callbacks, the interface can be confusing. The key idea is before starting up the server, the user registers a handler callback with gfserver library which controls how the request will be handled. The handler callback should not contain any of the socket-level code. Instead, it should use the gfs_sendheader, gfs_send, and potentially the gfs_abort functions provided by the gfserver library. Naturally, the gfserver library needs to know which request the handler is working on. All of this information is captured in the opaque pointer passed into the handler, which the handler must then pass back to the gfserver library when making these calls.

Submission

Read the documentation carefully for the requirements. When you are ready to turn in your code, use the command

python submit.py gfclient

to turn in your gfclient.c file and

python submit.py gfserver

to turn in your gfserver.c file.

Part 2: Implementing a Multithreaded Getfile Server

Note: For both the client and the server, your code should follow a boss-worker thread pattern. This will be graded. Also keep in mind this is a multi-threading exercise. You are NOT supposed to use fork() to spawn child processes, but instead you should be using the pthreads library to create/manage threads. You will have points removed if you don’t follow this instruction.

So far, the Getfile server can only handle a single request at a time. To overcome this limitation, you will make your Getfile server multi-threaded by modifying the handler in handler.c and updating gfserver_main.c as needed. The main, i.e. boss, thread will continue listening to the socket and accepting new connection requests. New connections will, however, be fully handled by worker threads. The pool of worker threads should be initialized to the number of threads specified as a command line argument. You may need to add additional initialization or worker functions in handler.c. Use extern keyword to make functions from handler.c available to gfserver_main.c. For instance, the main file will need a way to set the number of threads.

The revised command line interface should be as follows.

usage:

gfserver_main [options]

options:

-t [nthreads] Number of threads (Default: 2)

-p [listen_port] Listen port (Default: 8140)

-c [content_file] Content file mapping keys to content files

-h Show this help message.

Similarly on the client side, the Getfile workload generator can only download a single file at a time. In general for clients, when server latencies are large, this is a major disadvantage. You will make your client multithreaded by modifying gfclient_download.c. This will also make testing your getfile server easier. The revised command line interface should be as follows.

usage:

webclient [options]

options:

-h Show this help message

-n [num_requests] Requests download per thread (Default: 2)

-p [server_port] Server port (Default: 8140)

-s [server_addr] Server address (Default: 0.0.0.0)

-t [nthreads] Number of threads (Default 2)

In the client, a pool of worker threads should be initialized based on number of client worker threads specified with a command line argument. Each worker thread should issue up to a number of requests, also specified as a command line argument. You have flexibility in how your boss assigns download requests to the individual worker threads. One option is to statically make the decision before threads are created, and pass a per-thread workload descriptor at thread creation time. Another option is for the boss thread to maintain a queue of requests that are dynamically retrieved by the workers.

The folder mtgf includes the same files described above except that object files gfclient.o and gfserver.o may be used in-place of your own implementations.

Submission

Read the documentation carefully for the requirements. When you are ready to turn in your code, use the command

python submit.py gfclient_mt

to turn in your gfclient_download.c file and

python submit.py gfserver_mt

to turn in your handler.c and gfserver_main.c files.
