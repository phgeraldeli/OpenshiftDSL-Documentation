# OpenshiftDSL-Documentation

### OpenshiftDSL

Methods: 

* equals(); 
* getClass(); 
* hashCode(); 
* notify(); 
* notifyAll(); 
* toString(); 
* wait(); 
* _import(); 
* apply(); 
* cluster(); 
* create(); 
* delete(); 
* doAs(); 
* exec(); 
* expose(); 
* failUnless(); 
* getCapabilities(); 
* getLOGGER(); 
* getMetaClass(); 
* getProperty(); 
* idle(); 
* invokeMethod(); 
* logLevel(); 
* logToTaskListener(); 
* loglevel(); 
* newApp(); 
* newBuild(); 
* newProject(); 
* patch(); 
* policy(); 
* process(); 
* project(); 
* raw(); 
* replace(); 
* rsh(); 
* rsync(); 
* run(); 
* secrets(); 
* selector(); 
* serializableMap(); 
* set(); 
* setLockName(); 
* setMetaClass(); 
* setProperty(); 
* skipTLSVerify(); 
* splitNames(); 
* startBuild(); 
* tag(); 
* toSingleObject(); 
* unwrapOpenShiftList(); 
* verbose(); 
* verifyService(); 
* withCluster(); 
* withCredentials(); 
* withProject();

### OpenshiftDSL.create("*.yaml")/.selector("type", "name")/.related('pods')

Object:
selector(
    [name = "" ],
    [labels= "" ],
    [namelist= []],
    [projectlist= []]);

Methods:

* equals(); 
* getClass(); 
* hashCode(); 
* notify(); 
* notifyAll(); 
* toString(); 
* wait(); 
* $static_methodMissing(); 
* $static_propertyMissing(); 
* getErr(); 
* getMetaClass(); 
* getOperation(); 
* getOut(); 
* getProperty(); 
* getStatus(); 
* invokeMethod(); 
* methodMissing(); 
* propertyMissing(); 
* setMetaClass(); 
* setProperty(); 
* annotate(); 
* asJson(); 
* asYaml(); 
* autoscale(); 
* cancelBuild(); 
* count(); 
* delete(); 
* deploy(); 
* describe(); 
* exists(); 
* expose(); 
* freeze(); 
* label(); 
* logs(); 
* name(); 
* names(); 
* narrow(); 
* object(); 
* objects(); 
* patch(); 
* project(); 
* projects(); 
* related(); 
* rollout(); 
* scale(); 
* startBuild(); 
* union(); 
* untilEach(); 
* volume(); 
* watch(); 
* withEach();

### *.rollout()

Methods:

* equals(); 
* getClass(); 
* hashCode(); 
* notify(); 
* notifyAll(); 
* toString(); 
* wait(); 
* $static_methodMissing(); 
* $static_propertyMissing(); 
* cancel(); 
* getMetaClass(); 
* getProperty(); 
* history(); 
* invokeMethod(); 
* latest(); 
* methodMissing(); 
* pause(); 
* propertyMissing(); 
* resume(); 
* retry(); 
* setMetaClass(); 
* setProperty(); 
* status(); 
* undo();
