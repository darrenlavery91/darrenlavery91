-[ darren.lavery ~ ]# who
darren.lavery     certs/4 degree/1        2018-01-01 00:00 (196.168.1.1)
[ darren.lavery ~ ]# vim run_cv.sh
[ darren.lavery ~ ]# 
#!/bin/bash
echo "EDUCATION"
echo ""
echo "Red Hat – Certified System Engineer (RHCE)"
echo "(Credential ID 230-146-425)"
echo ""
echo "AWS– Cloud fundamentals"
echo "(Credential ID https://www.credly.com/badges/6623f7d8-4d6e-429e-8703-76d2a91553ea/public_url)"
echo ""
echo "HCIA-Cloud Service"
echo "(Credential ID 010102601747809243171409)"
echo ""
echo "Microsoft – Azure Fundamentals"
echo "March 2020 certified– No Expiration Date"
echo ""
echo "Red Hat – System Administrator (RHCSA)"
echo "(Attendance certification 2022)"
echo ""
echo "Microsoft – Azure Administrator"
echo "(Attendance certification  2022, Pending exam 2023)"
echo ""
echo "IBM Spectrum Scale Advance Administration H006"
echo "(Attendance certification  2023)"
echo ""
echo "IBM Spectrum Scale Basic Administration for Linux and AIX H005G"
echo "(Attendance certification  2022)"
echo ""
echo "Gordan Institute of Business Science"
echo "2017  - 2017"
echo "Managing for results certified"
echo ""
echo "BA Communications Degree UJ"
echo "2004 - 2009"
echo "Major in Visual and Audio Communication"
echo ""
echo "King Edwards VII School"
echo "2000 - 2004"
echo "Matric Certificate"
echo ""

grep -A 3 'work_experience:' ~/work_exp.yml
: wq!
[ darren.lavery ~ ]# cat ~/work_exp.yml
work_experience:
  - company: Multichoice - VOD Engineer
    date: Aug 2018 – Present
    description: (Long service 10 years at Multichoice SA – See profile)
  - company: Multichoice - Manager VOD 1st line Support
    date: Apr 2016 – Aug 2018
    description: Managed technical support while hands training was achieved, technical resolution time turn around was within 30 min for any issue raised.
  - company: DSTV Online - Multimedia Specialist
    date: Jan 2013 – Apr 2016
    description: Creating video profiles for all different “flavors” for multichoice VOD, from OTT to STB.
  - company: New Dimension Group – 3D animator / Video Editor
    date: Nov 2011 – Dec 2012
    description: Headed up the 3D animation department, found ways to automate tasks with JSON scripts using ADOBE products, and grew a love for IT.
  - company: Cam House – Video Editor
    date: Jan 2009 – Nov 2011
    description: Started as a camera man, learned video editing, and progressed into video animation.
[ darren.lavery ~ ]# grep info.py | head -18
import=os
skills = [
    "• Deadline driven",
    "• Team worker",
    "• Hard worker – Great positive attitude",
    "• Great communicator",
    "• Specialties: Red Hat Engineer, Python, yaml (ansible)bash scripting, Linux based backend server support, C++ microcontrollers, administrator on Azure cloud, AWS cloud, ffmpeg and Centos/ red hat 7 and 8.6.",
    "• Provide technical support in an environment that functions 24/7",
    "• Works closely with Operations and can Analyze, experience, pick trends and pains of Operations Offers short term workarounds"
]

for skill in skills:
    print(skill) 👋 Hi, I’m @darrenlavery91
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
darrenlavery91/darrenlavery91 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
