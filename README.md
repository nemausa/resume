### 个人信息

---

- **姓名**: 李文星
- **电话**: 136-8952-6320
- **邮箱**: tappanmorris@outlook.com
- **地址**: 深圳宝安
- **GitHub**: [nemausa](https://github.com/nemausa)
- **项目展示**: [查看项目](https://github.com/nemausa/resume/blob/master/lvgl_project_introduction.md)

### 求职意向

---

- **求职岗位**: C++程序员
- **期望薪资**: 面议

### 教育背景

---

- **学历**: 本科
- **学校**: 江西师范大学
- **专业**: 软件工程
- **毕业时间**: 2016
- **相关课程**: 数据结构、操作系统、嵌入式系统设计

### 技能

1. **深厚的C++基础**
   - 精通C++编程，扎实的语言底层功底与设计能力。
   - 熟练面向对象、模板编程及RAII机制，构建高性能、可扩展系统。
   - 深入理解STL容器、算法、智能指针和现代C++（11/14/17/20）特性。
2. **Qt、LVGL和AWTK开发**
   - 熟练使用Qt的信号槽机制、模型视图、多线程技术开发复杂界面。
   - 精通LVGL嵌入式界面开发，优化资源使用与高效事件处理。
   - 熟悉AWTK框架，在资源受限环境实现定制化UI解决方案。
3. **CMake与Makefile构建**
   - 精通跨平台、多模块自动化构建与精细化依赖管理。
   - 擅长通过CMake生成定制化Makefile，灵活优化构建流程。
4. **高效编辑器与环境配置**
   - 整合Visual Studio Code与Neovim，优化C++开发效率和体验。
5. **面向对象设计**
   - 精通SOLID设计原则与单例、工厂、观察者等常用模式。
   - 构建高内聚低耦合架构，提升系统的扩展性与可维护性。
6. **内存管理能力**
   - 深入理解智能指针底层实现与最佳实践，精细调控内存分配与回收。
   - 熟练手动管理与内存池技术，降低碎片及泄漏风险，实现性能稳定。
7. **高级调试技能**
   - 熟练使用gdb进行复杂C++程序精准调试。
   - 快速定位运行时错误、内存泄漏、崩溃问题，保障系统稳定高效。
8. **跨平台开发经验**
   - 熟悉Windows、Linux、macOS及FreeRTOS平台架构和开发机制。
   - 通过抽象与模块化设计，高效解决平台差异，确保代码可移植性。
9. **版本控制与CI/CD**
   - 精通Git，深入理解Git Flow、Trunk-Based Development等分支策略。
   - 熟练运用Rebase、Cherry-pick进行代码管理，搭建Git Hooks与CI/CD自动化流程。

### 项目经验


#### 陕汽重卡 (基于开阳1668e芯片)

- **项目描述** : 本项目旨在为陕汽重卡开发一套电话及音源控制系统，在驾驶过程中提升通信和娱乐体验。系统采用开阳1668e芯片，利用QT构建直观界面，实现电话功能与多音源管理，确保在复杂车载环境下保持通信稳定性与音质优异。
- **负责模块** :
    - **电话通信模块** ：负责接听、拨打、挂断、免提等电话操作。
    - **音源控制模块** ：支持收音机、蓝牙、USB媒体、内置存储等多种音频输入源的切换，并实现音量调节、均衡及数字信号处理。
    - **图形用户界面（GUI）模块** ：基于QT框架开发车载操作界面，实时展示电话状态、当前音源信息及其他关键数据，操作直观便捷。
    - **底层接口与通信模块** ：依托开阳1668e芯片，实现各模块之间的数据通信、接口管理及资源调度，并提供串口、蓝牙等调试接口。
    - **安全及容错管理模块** ：监控通信状态与音频异常，触发故障报警，并具备系统自恢复与重启机制，保证系统稳定运行。
- **使用技术** :
    - **C/C++** ：负责底层驱动和核心功能开发，实现高性能数据处理。
    - **QT框架** ：构建跨平台车载图形界面，实现高效、直观的用户交互。
    - **Linux/嵌入式RTOS** ：提供系统运行环境，满足实时任务调度和资源管理需求。
- **成果** :
    - 实现电话通信清晰稳定，保障车载通信质量。
    - 优化音源控制，多种音频输入源无缝切换，提升驾驶娱乐体验。
    - 提高系统响应速度和稳定性，有效应对重卡车载复杂环境的挑战。

---

#### 冰淇淋项目 (基于开阳630hv100芯片)

- **项目描述**: 该项目旨在设计、开发和集成一套汽车仪表系统，用于在驾驶过程中提供关键的车辆信息显示和与驾驶员的交互。系统的目标是通过优化显示模块、提升响应速度和安全性，增强驾驶体验。
- **负责模块**:
  - **显示模块**：负责汽车仪表盘的实时显示，包括车辆状态、速度、油量等关键数据。
  - **MCU（微控制器）**：处理与车辆传感器的数据通信和显示数据的传输。
  - **SOC升级**：进行系统升级，保证更好的性能和资源管理。
  - **蓝牙和串口通信**：实现蓝牙设备和仪表系统的连接，同时通过串口进行调试和通信。
  - **信号灯显示与报警**：管理汽车信号灯的显示，并在必要时触发报警。
  - **主题和语言切换**：为系统增加主题自定义和多语言支持功能，满足不同用户需求。
- **使用技术**:
  - **C**：核心功能和底层驱动开发。
  - **FreeRTOS**：实现实时任务调度和多任务管理。
  - **LVGL**：用于创建图形界面，实现高效的UI显示。
- **成果**:
  - 提高了系统的响应速度，使仪表盘显示更加流畅。
  - 优化了内存管理，减少了内存消耗，提升了系统稳定性。

#### 大冶项目 (基于全志T113芯片)

- **项目描述**: 旨在提供先进的用户界面和功能，提升用户体验，并确保操作的安全性。
- **主要功能**:

  - 驾驶辅助系统
  - 信息娱乐系统
  - 通信系统
- **负责模块**:

  - **信号灯显示与报警**: 实现了复杂的信号灯报警功能，提高了系统的警示能力。
  - **主题切换**: 开发了主题切换功能，增强了用户界面的个性化和可定制性。
  - **串口通信**: 实现了稳定的串口通信，确保了设备间的可靠数据传输和互动.
- **使用技术**:

  - **C++**: 用于实现核心功能和模块的开发。
  - **框架**: 使用了特定框架来提升系统的稳定性和方便修改。
- **成果**:

  - 成功集成复杂的信号灯报警功能，显著提升了系统的稳定性和可靠性。
  - 通过框架的使用，提高了系统的稳定性和维护性，便于后续的功能修改和扩展。

#### 空调选型服务器

- **项目描述**: 独立开发的一套高度并发的空调选型系统，支持多用户在线实时选型。通过输入用户的关键需求参数，如房间面积、气候条件、预算等，系统智能推荐最优空调方案。系统采用先进的分布式架构，能够在海量用户同时访问时，保证高效的任务分发与处理，并通过集群化设计提供弹性扩展能力，确保系统在高并发环境下的稳定运行。
- **使用技术**:
  - **C++**: 核心业务逻辑和高性能并发处理。
  - **SQL Server**: 后端数据库，用于存储用户数据及选型规则。
  - **Python**: 用于自动化任务、数据分析以及部分业务流程脚本化。
  - **IOCP**: 基于I/O完成端口技术，实现高效网络通信，支持数万用户的并发请求处理。
  - **分布式架构**: 采用微服务架构，系统的各个模块通过RPC进行相互通信，确保了服务间的低耦合性和高可扩展性。
  - **集群技术**: 使用集群化部署，将计算和存储任务分散到多个节点，支持负载均衡、故障切换、动态扩展等高级功能，显著提升了系统的容错性和整体吞吐量。
  - **Token认证**: 采用基于Token的认证机制，确保多用户在线操作的安全性和数据完整性。
- **成果**:
  - **系统稳定性大幅提升**：通过分布式架构和集群化部署，系统具备极强的容错能力和弹性扩展性。
  - **优化系统升级速度**：采用热更新和滚动升级策略，在不中断服务的情况下完成系统的无缝升级。
  - **性能提升**：显著提高了并发处理能力，系统可支持数万用户同时在线选型，处理速度较传统单服务器架构提升了。

### 工作经历

---

#### 恒勃控股股份有限公司

- **职位**: 软件工程师
- **工作时间**: 2024年10月 - 至今
- **工作描述**:
- 在恒勃控股担任核心软件工程师，全面负责面向车载仪表系统的软件架构设计与开发。工作中展现了卓越的全栈研发能力和嵌入式系统优化技巧
- 具体包括：

* **平台架构与框架定制** :
  * **AWTK UI框架定制** : 主导基于AWTK的UI框架设计与实现，在开阳芯片平台上针对硬件特性进行深度优化，打造低延迟、高响应性的仪表应用。
  * **LVGL UI框架优化** : 针对匠心创芯片环境，通过定制化和优化LVGL，构建流畅且图形精细的用户界面，有效利用有限硬件资源，保障系统在资源受限条件下依然保持出色显示效果。
* **高性能与跨平台优化** :
  * **多线程与事件驱动架构** : 应用先进的多线程设计和事件驱动模型（包括高效事件循环和异步I/O技术），显著提升系统在高并发交互场景下的响应速度和稳定性。
  * **硬件抽象层（HAL）集成** : 构建统一的硬件抽象层，精细管理底层硬件资源，实现各平台间的无缝切换和高度兼容，满足车载系统严格的实时性要求。
* **模块化与维护性提升** :
  * **面向对象与SOLID原则** : 采用面向对象设计和SOLID等架构原则，构建高内聚、低耦合的系统模块，确保后续功能扩展和系统升级的高效性，同时降低维护成本。
  * **自动化测试与CI/CD** : 设计并实施自动化测试、持续集成和部署流程，确保软件全流程高可靠性和快速迭代，显著提升交付效率与质量。
* **1668e平台仪表开发** :
  * **MVVM与Qt消息机制整合** : 引入MVVM设计模式，结合Qt原生信号槽和自定义消息中心，彻底实现UI展示层与业务逻辑层的解耦，推动数据自动绑定和实时交互。
  * **模块间高效通信** : 通过定制化的消息分发机制，实现异构模块间透明高效的通信，增强系统扩展性与灵活性，同时提升用户交互体验和系统整体稳定性。

#### 均锐科技有限公司

- **职位** : 软件工程师
- **工作时间** : 2023年6月 - 2024年9月
- **工作描述** :
- 在均锐科技担任T113 Linux平台核心研发工程师，主导车载仪表产品从UI设计到底层性能优化的全流程开发。负责系统调试、性能瓶颈排查与内存管理策略的制定，确保软件在高负载和实时响应场景下的卓越稳定性。通过与硬件团队的深度协作，实现软硬件资源的高效整合，从而满足严苛的车载应用需求。

 **关键成果与技术亮点** :

* **极速开机自检**
  * 深入剖析开机自检流程中的性能瓶颈，并采用并行自检算法和底层调度优化技术，将开机时间压缩至2.2秒内，显著提升了系统启动效率与用户体验。
* **内存管理与渲染优化**
  * 针对图片加载与渲染流程进行精细化管理，利用智能缓存与内存池策略，有效降低内存占用，优化了数据流通和图像预处理，显著减少了因内存溢出引起的崩溃风险。
* **系统稳定性与鲁棒性提升**
  * 构建自动化调试与测试框架，实现全流程性能监控及持续优化，在各种苛刻环境下保持系统高可靠性和低错误率，进一步提升了产品的市场竞争力。

#### 车可讯科技有限公司

- **职位** : 软件工程师
- **工作时间** : 2020年7月 - 2023年5月
- **工作描述** :
- 作为车载仪表系统的核心研发工程师，我全面主导了系统架构设计、关键功能实现以及全链路性能优化工作。负责软件与硬件的无缝整合，通过深入的代码调优和多线程/异步技术优化，确保系统在复杂实时应用场景中的高效运行与稳定性。同时，主导集成前沿车载通信与操作系统解决方案，如SOMEIP和AliOS，推动仪表系统向智能化、互联化方向演进。

 **关键成果与技术亮点** :

* **系统优化与性能提升** :
  * 利用多线程异步处理和精细化代码调优，实现系统响应速度提升20%，同时将内存占用降低15%，显著改善高并发场景下的整体运行表现。
  * 构建全链路性能监控体系，通过实时数据分析识别并优化关键瓶颈，确保系统在极限负载下依然保持流畅运行。
* **高可靠性设计与关键Bug修复** :
  * 深入排查并解决界面切换崩溃问题，采用堆栈跟踪与自动化回归测试等技术，显著降低系统崩溃率，从而大幅提升系统稳定性与用户满意度。
  * 实现了按钮电压滤波算法，有效稳定了硬件按键输入，优化了用户交互体验及响应准确性。
* **前沿技术集成与平台开发** :
  * 主导SOMEIP通信协议的集成，构建轻量级车载服务通信架构，实现跨模块数据共享和实时响应，提升车载网络通信的可靠性与扩展性。
  * 负责AliOS平台的开发与适配，使软件在底层操作系统上的运行更加高效和安全，支持不同硬件配置之间的无缝衔接。

#### 麦克维尔空调有限公司

- **职位**: 软件工程师
- **工作时间**: 2017年6月 - 2020年6月
- **工作描述** :
- 在麦克维尔空调担任核心软件工程师，主导空调选型系统的整体架构设计、全流程优化及跨平台性能调优工作，确保系统在高并发和复杂业务场景下的卓越稳定性与高效响应。主要负责前后端全栈开发及跨部门协作，通过精细化性能分析和持续优化，实现了系统与运维流程的全面升级。

 **关键成果与技术亮点** :

* **系统稳定性与用户体验的全面提升**
  * **错误率降低90%** : 通过深入分析系统瓶颈并实施高效的资源调度及容错机制，成功将系统错误率降低90%，显著提升整体稳定性。
  * **客户满意度飙升** : 优化用户交互及响应机制，加速业务流程，极大改善用户体验，进而提升客户留存率和市场口碑。
* **卓越的性能优化**
  * **内核级调优与资源管理** : 深入挖掘Linux服务器内核瓶颈，运用智能缓存、实时监控及自动化测试策略，对关键系统指标（错误率、响应时延）实现精细管控，并通过动态扩容策略将系统处理能力提升达5倍。
  * **跨平台网络编程** :
    * 在Linux平台上，充分利用 **epoll** 高效多路复用技术，构建低延迟、高吞吐的事件驱动架构，实现超大规模连接精准管理。
    * 在Windows平台上，通过 **IOCP** 异步I/O模型，最大化系统资源利用率与响应速度，确保不同平台间一致性表现。
    * 融合微服务架构、负载均衡与智能缓存，形成全链路性能监控与动态优化体系，确保零停机和实时性需求。
