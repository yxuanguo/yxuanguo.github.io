<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yixuan Guo - Taiyuan University of Technology</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Helvetica Neue", Arial, sans-serif;
        }
        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
            padding: 40px 20px;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: #fff;
            padding: 50px;
            border-radius: 8px;
            box-shadow: 0 2px 12px rgba(0,0,0,0.08);
            display: flex;
            gap: 50px;
            flex-wrap: wrap;
        }
        /* 左侧：照片+基本信息 */
        .sidebar {
            flex: 0 0 220px;
        }
  .profile-img {
    width: 260px; /* 照片宽度，觉得大/小可以改这个数字 */
    height: auto; /* 高度自动，保持原始比例 */
    border-radius: 6px;
    background-color: #e9ecef;
    margin-bottom: 20px;
}
        .sidebar h1 {
            font-size: 24px;
            margin-bottom: 8px;
            color: #1a365d;
        }
        .sidebar .title {
            color: #4a5568;
            font-size: 16px;
            margin-bottom: 15px;
        }
        .sidebar .contact {
            font-size: 14px;
            color: #718096;
            word-break: break-all;
        }
        .sidebar .contact p {
            margin-bottom: 6px;
        }

        /* 右侧：简历内容 */
        .content {
            flex: 1;
            min-width: 300px;
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            color: #1a365d;
            font-size: 20px;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 6px;
            margin-bottom: 15px;
        }
        .section ul {
            list-style: none;
            padding-left: 0;
        }
        .section li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }
        .section li::before {
            content: "•";
            position: absolute;
            left: 0;
            color: #2b6cb0;
            font-weight: bold;
        }
        .pub-item {
            margin-bottom: 12px;
            font-size: 14.5px;
        }
        .pub-item .venue {
            font-style: italic;
            color: #2d3748;
        }
        .pub-item .note {
            color: #718096;
            font-size: 13px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 左侧栏：照片+基本信息 -->
        <div class="sidebar">
            <!-- 照片：把你的证件照命名为 profile.jpg 上传到仓库根目录即可显示 -->
            <img src="profile.jpg" alt="Yixuan Guo" class="profile-img">
            
            <h1>Yixuan Guo</h1>
            <div class="title">Associate Professor</div>
            <div class="title">College of Electronic Information Engineering<br>Taiyuan University of Technology</div>
            
            <div class="contact" style="margin-top: 20px;">
                <p><strong>Email:</strong> guoyixuan@tyut.edu.cn</p>
                <p><strong>Address:</strong> Taiyuan, Shanxi, China</p>
            </div>
        </div>

        <!-- 右侧主内容 -->
        <div class="content">
            <!-- 研究方向 -->
            <div class="section">
                <h2>Research Interests</h2>
                <ul>
                    <li>Wireless Communications and Beamforming</li>
                    <li>Resonant Beam Based Integrated Sensing and Communication (ISAC)</li>
                    <li>Passive Indoor Positioning and Localization</li>
                    <li>Wireless Power Transfer (WPT) and SWIPT</li>
                    <li>MIMO Systems and UAV Networks</li>
                </ul>
            </div>

            <!-- 教育经历 -->
            <div class="section">
                <h2>Education</h2>
                <ul>
                    <li>
                        <strong>Ph.D. in Intelligent Science and Technology</strong><br>
                        Tongji University, Sep. 2022 – Jun. 2026<br>
                        Joint Training: Shanghai Artificial Intelligence Laboratory<br>
                        Advisors: Prof. Gang Yan, Prof. Qingwen Liu
                    </li>
                    <li>
                        <strong>M.S. in Software Engineering</strong><br>
                        Northwest Normal University, Sep. 2019 – Jun. 2022<br>
                        Advisor: Prof. Xiangdong Jia
                    </li>
                    <li>
                        <strong>B.E. in Software Engineering</strong><br>
                        Shanxi University, Sep. 2014 – Jun. 2018<br>
                        Minor: Accounting (Double Degree)
                    </li>
                </ul>
            </div>

            <!-- 期刊论文 -->
            <div class="section">
                <h2>Selected Journal Publications</h2>
                <div class="pub-item">
                    [1] Y. Guo, et al. Resonant Beam Enabled DoA Estimation in Passive Positioning System.
                    <span class="venue">IEEE Transactions on Wireless Communications</span>, 2024.
                    <span class="note">(CAS Zone 1, IF=10.7)</span>
                </div>
                <div class="pub-item">
                    [2] Y. Guo, et al. Resonant Beam Enabled Passive 3D Positioning.
                    <span class="venue">IEEE Internet of Things Journal</span>, 2025.
                    <span class="note">(CAS Zone 1, IF=8.9)</span>
                </div>
                <div class="pub-item">
                    [3] Y. Guo, et al. Resonant Beam Multi-Target DOA Estimation.
                    <span class="venue">IEEE Internet of Things Journal</span>, 2026.
                    <span class="note">(CAS Zone 1, IF=8.9)</span>
                </div>
                <div class="pub-item">
                    [4] J. Mu#, Y. Guo#, et al. 3D Passive Positioning with Individual Resonant Beam Base Station.
                    <span class="venue">IEEE Transactions on Green Communications and Networking</span>, 2026.
                    <span class="note">(Co-first author, CAS Zone 2, IF=6.7)</span>
                </div>
                <div class="pub-item">
                    [5] J. Mu, Y. Guo, et al. A Low LO Frequency Resonant Beam System for Multi-User Self-Aligning SWIPT.
                    <span class="venue">IEEE Internet of Things Journal</span>, 2026.
                    <span class="note">(Supervised student as first author, CAS Zone 1)</span>
                </div>
                <div class="pub-item">
                    [6] X. Jia, Y. Guo, et al. Age of Information and Energy Efficiency of AF Relay-Assisted IoT with Non-Linear Energy Harvesting.
                    <span class="venue">Transactions on Emerging Telecommunications Technologies</span>, 2022.
                    <span class="note">(CAS Zone 4, IF=2.5)</span>
                </div>
            </div>

            <!-- 会议论文 -->
            <div class="section">
                <h2>Conference Publications</h2>
                <div class="pub-item">
                    [1] Y. Guo, et al. RF-RBComm: Pilotless Beamforming and Uplink-Downlink Frequency Separation Method.
                    <span class="venue">IEEE/CIC ICCC Workshops</span>, Shanghai, China, 2025. (EI)
                </div>
                <div class="pub-item">
                    [2] Y. Guo, et al. Outage Performance Evaluation for Drone Assisted Three-Dimensional Heterogeneous Networks.
                    <span class="venue">IEEE VTC2021-Fall</span>, Norman, OK, USA, 2021. (EI)
                </div>
                <div class="pub-item">
                    [3] Y. Guo, et al. Analysis of Downlink Coverage and Capacity for 3D Mobile UAV Networks.
                    <span class="venue">IEEE ISMII</span>, Zhuhai, China, 2021. (EI)
                </div>
            </div>

            <!-- 专利 -->
            <div class="section">
                <h2>Patents</h2>
                <div class="pub-item">
                    [1] Q. Liu, Y. Wu, Y. Guo. Radio Positioning and Early Warning Method and System for Maneuvering Vehicle Area.
                    <span class="note">CN Patent, Publication No. CN116609723A, 2023.</span>
                </div>
                <div class="pub-item">
                    [2] Q. Liu, S. Han, S. Du, Y. Guo, et al. Integrated System and Method for Power Supply, Positioning and Communication Based on Resonant Beam.
                    <span class="note">CN Patent, Publication No. CN116961253A, 2023.</span>
                </div>
                <div class="pub-item">
                    [3] Q. Liu, S. Du, Z. Zhang, et al. Clustered UAV Ad Hoc Network Communication Architecture.
                    <span class="note">CN Patent, Publication No. CN119052881A, 2024.</span>
                </div>
            </div>

            <!-- 科研项目 -->
            <div class="section">
                <h2>Research Projects</h2>
                <ul>
                    <li>National Key R&D Program of China (2022YFA1004700), 2022–2027. <span class="note">(Student Lead)</span></li>
                    <li>Tongji University Interdisciplinary Key Project: CPS Fault Diagnosis Platform for UAV Swarms, 2022–2027. <span class="note">(Participant)</span></li>
                    <li>NSFC General Program: Distributed Laser Mobile Charging Technology (61771344). <span class="note">(Participant)</span></li>
                    <li>Gansu Provincial Science and Technology Program: Key UAV Technologies (18YF1GA060). <span class="note">(Participant)</span></li>
                    <li>Postgraduate Innovation Star Project of Gansu Province (2021CXZX-268), 2021. <span class="note">(Principal Investigator)</span></li>
                </ul>
            </div>

            <!-- 荣誉奖项 -->
            <div class="section">
                <h2>Awards & Honors</h2>
                <ul>
                    <li>First-Class Academic Scholarship, Northwest Normal University, 2021</li>
                    <li>Third Prize, "Challenge Cup" Gansu Provincial College Students' Academic Competition, 2021</li>
                    <li>Outstanding Member, CCF Northwest Normal University Student Chapter, 2021</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
