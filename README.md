This is the parent for the ecg-analysis project.

```
git clone git@github.com:pangratz/ecg-analysis-parent.git
cd ecg-analysis-parent
git submodule init
git submodule update
cd physiotoolkit-wrapper
rake
cd ..

mvn clean package
```