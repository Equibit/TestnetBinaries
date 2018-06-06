# TestnetBinaries
Equibit Testnet Binaries Distribution

## Welcome to the Equibit Testnet
This repository contains executables for the Equibit network. For more information about Equibit, please visit www.equibitgroup.com.

## Downloadable Binaries
The binaries included in this repository are NOT production ready. Equibit Group is distributing this software to a selected group of miners and blockchain operators who have signed a Letter of Intent (LOI) to provide hashing power for the future Equibit Mainnet.

Our software toolchain currently only compiles binaries for Ubuntu (16.04). We intend on also creating 64-bit Windows binaries very shortly. Likewise, we will be adding binaries for a modified version of bfgminer that supports the Equibit block structure and protocol.  

## Expectations Management
Volunteers are welcome to download and install these binaries, provided they agree with the terms and conditions below. In short: this is an unfinished work. We are inviting a limited set of volunteers to join the Testnet to *debug* the application. This application will crash. This application will segfault. This application will lose connectivity. This application is under development.

Once the Testnet period is over, a production-ready Mainnet application will be launched to the general public. Please stay tuned to our Telegram channel for additional details about our roadmap and launch schedule: https://t.me/Equibit

## How to run the Binaries
The binaries were compiled to run on Ubuntu 16.04. 64-bit Windows binaries will also be provided shortly. Equibit is a modified fork of the Bitcoin repository. Most Bitcoin dependencies and APIs are shared with Equibit. Additional details to follow.

### Port forwarding
To allow incoming connections to your Equibit node, port 8330 needs to be open.

For this step, you need to know the local IP address of the computer running Equibit Core.

Login to your router. Look for an option called Port Forwarding, Port Assignment, or anything with “Port” in its name. On some routers, this option is buried in an Applications & Gaming menu.

The port forwarding settings should allow you to map an external port on your router to the “internal port” of a device on your network. Both the external port and the internal port should be 8330 for Equibit.

After filling in the details for the mapping, save the entry. You should not need to restart anything. Start Equibit Core (if you haven’t already).

### Dependencies (see Wiki section for instructions)
Boost 1.58

libevent-2.0

## Roles and Responsibilities
The goal is to launch a successful Equibit network. We welcome all contributions and expertise that will help make that goal a reality. Everyone who has been given access to this repository has unique experience with peer-to-peer network. Let's all be respectful of each other and operate under the basis of peers working with peers.  

The Equibit network needs our expertise in running nodes, but also in setting up a good community management process, documentation, community leadership, and more. Please make sure to join the Equibit Testnet A-Team channel on Telegram by contacting christian@equibitgroup.com.

### Terms and Conditions
#### Disclaimer of Warranty. 
Unless required by applicable law or agreed to in writing, Licensor provides the Work (and each Contributor provides its Contributions) on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied, including, without limitation, any warranties or conditions of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE. You are solely responsible for determining the appropriateness of using or redistributing the Work and assume any risks associated with Your exercise of permissions under this License.

#### Limitation of Liability. 
In no event and under no legal theory, whether in tort (including negligence), contract, or otherwise, unless required by applicable law (such as deliberate and grossly negligent acts) or agreed to in writing, shall any Contributor be liable to You for damages, including any direct, indirect, special, incidental, or consequential damages of any character arising as a result of this License or out of the use or inability to use the Work (including but not limited to damages for loss of goodwill, work stoppage, computer failure or malfunction, or any and all other commercial damages or losses), even if such Contributor has been advised of the possibility of such damages.

#### Accepting Warranty or Additional Liability. 
While redistributing the Work or Derivative Works thereof, You may choose to offer, and charge a fee for, acceptance of support, warranty, indemnity, or other liability obligations and/or rights consistent with this License. However, in accepting such obligations, You may act only on Your own behalf and on Your sole responsibility, not on behalf of any other Contributor, and only if You agree to indemnify, defend, and hold each Contributor harmless for any liability incurred by, or claims asserted against, such Contributor by reason of your accepting any such warranty or additional liability.
