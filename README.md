# Sightline-ai_FutureForge

*Explainable Road Visibility and Near-Miss Risk Intelligence*

Team: Future Forge
Hackathon: DEXATHON — Open Innovation
Team ID: DEX26117
Project Category: Software

**Overview**
SightLine AI is a proposed computer-vision system designed to help investigate pedestrian visibility risks using traffic video.

Pedestrians may be partially or fully obscured by parked vehicles, buses, and other roadside obstacles. These obstructions can create situations in which approaching drivers may have limited opportunities to notice pedestrians.

SightLine AI aims to analyse road-user movements, estimate obstruction-related visibility from a defined driver viewpoint, and present potentially risky events as explainable video evidence for human review.

Project status: Prototype planning and development. The proposed capabilities have not yet been validated for real-world road-safety use.

**Problem Statement**
Conventional traffic-video analysis can help identify road users and potentially dangerous interactions. However, determining how roadside obstructions may affect a pedestrian's visibility from a driver's viewpoint requires additional geometric analysis.

SightLine AI explores how video-based visibility estimation could help road-safety auditors and traffic engineers investigate these situations more systematically.

**Proposed Solution**
The system is planned to:

Detect and track pedestrians and vehicles in selected traffic videos.

Identify potential obstruction-related pedestrian visibility events.

Estimate when a pedestrian becomes geometrically visible from a defined driver viewpoint.

Examine hypothetical obstruction-position changes to explore their possible effect on visibility.

Generate annotated video evidence and event reports for human review.

These are intended capabilities; their feasibility and accuracy will be assessed during development.

Key Differentiator
SightLine AI focuses on estimated pedestrian visibility and the potential role of roadside obstructions, rather than relying only on object detection or proximity-based risk indicators.

The project aims to connect visibility estimates with supporting video evidence, uncertainty information, and hypothetical obstruction scenarios.

The distinctiveness of this approach will be assessed against existing research and road-safety systems before any claim of proven novelty is made.

**Technical Approach**
Planned workflow:

Traffic Video → Object Detection and Tracking → Camera and Scene Calibration → Geometric Visibility Analysis → Event Evidence → Human Review Dashboard

Planned Technology Stack
Component	Technology
Programming language	Python
Video processing	OpenCV
Object detection and tracking	YOLO-based tools
Visibility estimation	Geometric modelling
Backend API	FastAPI
Dashboard	Streamlit or React
Data storage	SQLite
The final implementation may change based on prototype testing and technical feasibility.

**Expected Outputs**
Annotated traffic-video frames

Pedestrian visibility timelines

Potential obstruction-related event reports

Supporting video evidence for human review

Exploratory comparisons of hypothetical obstruction positions

These outputs are planned and should not be interpreted as completed features unless demonstrated in the repository.

**Feasibility and Validation Plan**
The initial prototype will focus on a limited set of suitable video clips and a fixed-camera scenario.

Planned validation activities include:

Select suitable video footage with appropriate usage permissions.

Manually label relevant pedestrian visibility and obstruction events.

Compare system estimates against human-reviewed annotations.

Examine detection, tracking, calibration, and visibility-estimation errors.

Document limitations and determine what further testing is required.

Roadside-camera footage does not automatically establish what a real driver could see. Results will therefore be treated as geometric estimates, not direct measurements of driver perception.

Intended Users
Road-safety auditors
Traffic engineers
Municipal road authorities
Urban planners
Road-safety researchers

SightLine AI is intended as a potential decision-support tool, not an autonomous authority for declaring a road safe or unsafe.

Potential Impact
If successfully developed and validated, SightLine AI could help reviewers organise video evidence, investigate visibility-related hazards, and prioritise locations for further road-safety assessment. Its actual usefulness, accuracy, and economic benefits remain to be established through testing and user feedback.

Team
Future Forge
DEXATHON | Open Innovation | Software
Team ID: DEX26117

Disclaimer
SightLine AI is an experimental student project. Its estimates are not a substitute for professional road-safety audits, field inspections, or validated engineering assessments. No reduction in crashes or other safety outcomes is claimed at this stage.
