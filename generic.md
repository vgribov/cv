# Vsevolod Gribov #

![](./userpic.png)

## Summary ##

An embedded C/C++ (and Go) developer with a simplistic approach.

I started writing my first C/C++ programs and discovering the Linux kernel in middle school. Now, I
hold a Master of Science in Engineering and have 15 years of experience in areas ranging from
machine control systems to networking, automotive and aviation. My passion is to make things
simpler, faster and safer.

An overview of my career includes these highlights:

- **AERQ GmbH**: As a senior embedded developer, I ported LG's WebOS to the 64-bit *VMware*
  platform. I wrote a simple *Wayland* compositor based on hardware planes that enabled 4K
  DRM-protected video playback on the *NXP i\.MX 8M* platform. I've integrated *Qt* applications as
  lightweight *systemd*-containers, learned *Golang* and implemented a custom *K8s* controller to
  install them on all in-seat displays in a cluster.
- **Luxoft GmbH**: As a senior C++ developer, I worked with the *Qt* framework on behalf of Daimler
  to build their in-car infotainment system. I focused mostly on stability and performance issues
  and communication with backend car services. I also participated in porting the HMI to the
  Android platform.
- **Larch Networks**: As a lead developer, I've participated in creating the *OpenSwitch* ASIC
  plugin for the newest *Marvell Bobcat 3* packet processor. Then, as a team lead, I ported it to
  the *Cortex-A9* CPU with the *Aldrin* packet processor. I've also developed "from scratch" a
  *DHCPv6* server for Panasonic enterprise switches, written using only the C++ standard library
  and Linux syscalls.
- **UnIT**: Working mostly with *Qt*, I've developed workstation software for an excise stamp
  quality control system, a fingerprint recognition system, and a mobile passport issuance system.
- **SKBIS**: As a result of my university research, I've developed an automatic position sensor
  adjustment system based on the Texas Instruments *TMS320* DSP and the *iC-MQ* interpolator. I
  developed firmware for most of the machine tool position control system modules and wrote parts
  of the high-speed logic (mostly counters) in *Verilog*.

## Advanced C/C++ knowledge

I started writing my first C and C++ programs in the 8th grade. Since then, I've written programs
mostly for embedded systems, starting with small *AVR* bare-bones applications and ending with
complex networking open-source projects such as OpenSwitch and *Qt*-based HMIs for automotive and
aviation.

In 2014, I got carried away with *modern C++*. At Larch Networks, I've written a *DHCPv6* server
using only the *C++11* standard library. Since then, I've tried to stay aligned with the latest C++
standards (up to *C++20*) and follow the *Core Guidelines*. At Luxoft and AERQ I've participated in
the hiring process and performed dozens of C/C++ coding interviews.

## Experience with the Qt Framework (desktop/embedded)

Tired of Microsoft's MFC during my work in SKBIS I decided to try *Qt*. At that time, it was
Trolltech's Qt 4. Then I moved to Kyiv and started to work in UnIT, where I developed Qt-based HMIs
for an excise stamp quality control system and a mobile passport issuance system.

At Luxoft, working on in-car infotainment systems for Daimler, I learned *QML* and gathered lots of
experience with *Qt/QML* safety, performance and stability issues. I applied this knowledge later
at AERQ, where in just one month I wrote a simple Qt browser application to replace the slow
JS-based UI for the new in-flight entertainment system.

## Solid understanding of embedded Linux

In the programming classes in the middle school, we used FreeBSD on our workstations and discovered
the *Linux kernel* sources. Lately, I've studied Linux from different angles. At Larch Networks,
I've ported Linux to at least three different embedded *ARM*-based platforms, adjusting both
*U-Boot* and *Linux kernel* sources and writing custom *device trees* based on schematics. I've
used *BuildRoot*, *Yocto* and even some handwritten scripts to generate a simple Linux root file
system.

At AERQ I started using *Systemd* containers and *portable services* and wrote *BitBake* receipts to
produce minimal root filesystems and SDKs for them. I also wrote a simple *Wayland* compositor
based on *libdrm* and *EGL* to enable hardware-accelerated video playback on the *i\.MX 8M*
platform.

## Experience with containers, Kubernetes and Go

I started to use *Docker* at Larch Networks as a lightweight virtual machine to set up clean
development environments for different target platforms. Working on the *OpenSwitch* ASIC plugin, we
used *pytest* and *Docker containers* to create simple network topologies for testing.

At AERQ, due to some aviation regulations, we containerize all user applications, which can be
either web-based or native. In-seat displays form a large distributed system, which is split into
*K8s clusters* to increase reliability and share hardware resources. The whole system is declared
as a collection of *K8s resource definitions* and controlled by *K8s controllers*. We also deploy
some pluggable functionality, which should be available *before* the cluster is set up, as *Systemd
portable services*.

I am working to integrate native applications, which are run as *Systemd containers* and deployed
on each in-seat display as *OCI images* by a custom *K8s* controller written in *Go*. We use
*buildah* and *Yocto* to produce optimized application images and portable services.

## Real-life experience with networking protocols and Marvell chips

I have been working in networking for more than two and a half years at Larch Networks. I worked on
creating a security *WiFi USB dongle* based on *TI Sitara SOC* and *WL1837MOD*. I also participated
in developing a *FreeRTOS* based solution for clever unmanaged switches with Marvell's *AlleyCat3*,
*BobCat2* and *BobK* packet processors inside. I worked both with the Marvell's *CPSS* library and
packet processor registers directly, setting up *Multicast groups*, *VLANs* and different policies.
I developed parts of the *OpenSwitch* ASIC plugin for *BobCat3*, implementing *access lists*, *VLAN
interfaces*, and *L3 routing*. I developed "from scratch" a *DHCPv6* server and ported the
Marvell's *FPA* library to the *Aldrin* packet processor.

## Knowledge of microcontrollers, schematics and measurement technologies

During my work at Larch Networks, I dealt with complex schematic diagrams of network equipment to
configure *device trees* and adjust *Linux kernel modules* to the boards' hardware. At SKBIS, I
designed and implemented a measurement device based on the *TMS320 DSP*, which was used to adjust
*optical motion sensors*. I worked with *Altium*, *Multisim*, and *Quartus* and had some
experience with *Altera FPGAs* and *Verilog*. I also wrote firmware for several modules of the
position control system, which were based on *AVR ATmega* and *AT90* chips.

## Scripting languages for testing and automation

I love to use *Perl* to automate my everyday development tasks — for automation, as a better
*bash*, or as a powerful text processing tool.

Working on the OpenSwitch ASIC plugin, I started to use *Python*, as OpenSwitch uses *pytest* for
functional testing. Since then, I prefer to use *Python* to write something quickly, mostly because
of its libraries. For example, at Luxoft I automated the whole API migration process with several
*Python* scripts that analyzed API changes, created corresponding JIRA tasks, and assigned them to
the developers responsible for the components affected by the changes.

## Experience with various collaboration software

I used to work with various task tracking systems and collaboration software, such as *Redmine*,
*GitLab*, *BitBucket*, *Jira*, *Confluence*, *Slack* and *MS Teams*.

I mostly use *Git* as a version control system, but I also have some experience
with *SVN* and *CVS*.

## Creativity with a focus on simplicity

Years of experience in embedded development taught me that resources are limited. Thus, I prefer
simple solutions closer to the system level with fewer dependencies and overhead. I also try to
advocate such solutions and propose corresponding changes on different levels.

When I came to AERQ, I quickly noticed that the current approach where parts of the main UI are
implemented as JS-based web-applications running in a *chromium* processes is too expensive for an
embedded system. I proposed a simpler *Qt*-based solution and in one month wrote a POC application
implementing most of the existing UI components, which convinced our management to replace *WebOS*
with an own *Yocto*-based operating system optimized for our needs.

## Self-learning ability

Most of the things I know, I've learned from books and online articles. I like to learn new things
and then apply them in my work.

In AERQ we decided to use *Kubernetes* to control and configure our in-flight entertainment system.
My task was to implement deployment of native applications on in-seat displays. In 3 months, I
learned *Kubernetes API* and *Golang* and implemented a custom controller which deploys native
applications according to corresponding resource definitions.

## Communication and leadership skills

For the last 8 years I've worked in international teams, communicating in different languages over
e-mail, *Slack*, *Zoom* and *MS Teams*, assigning tickets, and making code reviews on *Gerrit* and
*GitLab*.

My colleagues note my open and direct way of communication, focused on solving the problem. I try
to encourage transparency and knowledge sharing inside the team and establish a direct
communication with other teams. In Larch Networks, I also had six months of experience leading a
team of five developers.

## Employment

### Senior Software Developer at AERQ, Germany

<http://www.aerq.com>

 - **Dates**: 2021 - now.
 - **Company description**: A startup established by Lufthansa Technik and LG Electronics to
   develop an innovative in-flight entertainment platform.
 - **Responsibilities**: Integration of Qt-based native applications. Wayland compositor, enabling
   hardware accelerated video-playback. System logging and monitoring. Porting WebOS to VMware
   virtual machine. Research.

### Senior C++ Developer at Luxoft, Germany

<http://www.luxoft.com>

 - **Dates**: 2018 - 2021.
 - **Company description**: an international software development company with more than 13,000
   employees, 42 offices in 21 countries in North America, Western and Eastern Europe, Asia
   Pacific, and South Africa.
 - **Responsibilities**: Embedded software development for automotive equipment. HMI and system
   programming in C++ and QML. Software stability, performance analysis and communication with
   backend services.

### Senior C++ Developer at Luxoft, Ukraine

<http://www.luxoft.com>

 - **Dates**: 2017 - 2018.
 - **Company description**: an international software development company with more than 13,000
   employees, 42 offices in 21 countries in North America, Western and Eastern Europe, Asia
   Pacific, and South Africa.
 - **Responsibilities**: Embedded software development for automotive equipment. HMI and system
   programming in C++ and QML. Implementation of communication protocols with backend services.

### Developer and Team Leader at Larch Networks, Israel

<http://www.larch-networks.com>

 - **Dates**: 2015 - 2017.
 - **Company description**: A systems engineering, implementation and deployment company.
 - **Responsibilities**: Embedded software development for networking equipment. Board bring-up.
   Network Protocols implementation. Business trips and work at the customer's side. Setting tasks
   and writing reports.

### Developer at UnIT, Ukraine

<http://unit.com.ua>

 - **Dates**: 2014 - 2015
 - **Company description**: Ukrainian IT company, leader of national automated computer systems
   development and integration market.
 - **Responsibilities**: Workstation software development.

### Software Engineer at RIVS, Russia

<http://www.rivs.ru>

 - **Dates**: 2013 - 2014
 - **Company description**: Russian company, which comprehensively solves the problem of mineral
   processing.
 - **Responsibilities**: Software development for analyzer. Research.

### Software Engineer at SKBIS, Russia

<http://www.skbis.ru>

 - **Dates**: 2008 - 2013
 - **Company description**: Russian manufacturer of motion sensors for mechanical engineering.
 - **Responsibilities**: Embedded and workstation software development. Schematics development.
   Board bring-up. Preparation of specifications and documentation. Research.

## Education

 - In 2002, graduated from Anichkov Lyceum in St. Petersburg and entered the Faculty of Technical
   Cybernetics of Saint-Petersburg State Polytechnic University, Department of Information Systems
   for Environmental Safety.
 - In 2006, defended perfectly the work on the "X-ray inspection system for welded joints" at
   Saint-Petersburg State Polytechnic University and received a bachelor's degree in engineering
   and technology in the direction of "Instrument making"
 - In 2008, defended an excellent thesis on "The automatic adjustment system for optical motion
   sensors" at Saint-Petersburg State Polytechnic University and received a master's degree in
   engineering and technology in the direction of "Instrument making", specialized on
   "Microprocessor tools and measurement software".

## Human languages

English, German, Ukranian and Russian

## Personal information

A few years ago, I used to spend all my holidays in the mountains with my snowboard. Now, apart
from coding, I spend them with my family, reading books, travelling and doing all sorts of
nonsense with my 7-year-old son. I also love music. Sometimes I even play it, at home.

## Contact Settings ##

Please don't hesitate to reach me via my [e-mail](mailto:seva.grbv@gmail.com).

