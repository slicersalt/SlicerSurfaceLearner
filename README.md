What is this project ?
This project is NOT the official SlicerSurfaceLearner repository.

It is a fork of SlicerSurfaceLearner sources hosted at https://github.com/mturja-vf-ic-bd/SlicerSurfaceLearner.

It is used as staging area to maintain and test patches that will be contributed back to the official repository.

What is the branch naming convention ?
Each branch is named following the pattern slicer-YYYY-MM-DD-vY.Y.Z-SHA{7}

where:

vX.Y.Z is the version of the forked project
YYYY-MM-DD is the date of the last official commit associated with the branch.
SHA{7} are the first seven characters of the last official commit associated with the branch.
For more details, see https://www.slicer.org/wiki/Documentation/Nightly/Developers/ProjectForks

How to update the version of SlicerSurfaceLearner ?
Clone this repository and add a remote to the official project
git clone git://github.com/slicersalt/SlicerSurfaceLearner
cd SlicerSurfaceLearner
git remote add upstream https://github.com/DCBIA-OrthoLab/SlicerSurfaceLearner
git fetch upstream
Create a new branch following the convention slicer-YYYY-MM-DD-vY.Y.Z-SHA{7}

Cherry-pick the Slicer specific commits from last branch. Resolve conflict as needed.

To test the changes, locally rebuild Slicer.

Publish the branch. (directly in this repo if you have push rights, or on a fork)

Update Slicer SlicerSurfaceLearner external project and submit a pull request.

How to be granted push rights ?
Ask on https://discourse.slicer.org/c/community/slicer-salt

Questions
If you have questions, see https://discourse.slicer.org/c/community/slicer-salt