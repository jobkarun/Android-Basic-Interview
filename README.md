# Android Basic Interview
                                           Android Basic Interview Questions
                                                        
                                                     


## Phase I

* What is android and Why Android?
* Who is the founder of Android? Andy Rubin, Rich Miner, Nick Sears
* Android version and API level
* History of android
* What are Advance Features of Android OS?
* What do you think are some disadvantages of Android?
* Tools Required for Developing Android Apps? JDK,ADT,SDK,ADB,Android Studio
* What is .dex and why use .dex ?
* What are different ART vs Dalvik
* What is an APK format?
* Which kernel is used in Android?
* Explain the Android Architecture.
* What is an Android Manifest file?
* What is the Open Handset Alliance?
* What is a resource?
* What is a Loader?
* What is Lint?  What is it used for?
* What is a SurfaceView?
* Describe Android Application Architecture.
* What is ADB?
* What is ANR? How can the ANR be prevented?
* What is DDMS and what can you do with it?
* What is AAPT?
* Explain Android notification system?
* Additional Components-Fragments, Views, Layouts, Intents, Resources, Manifest.
* Manifest file to specify different Android application components 
    ```
      activity,service,receiver,provider
    ```
* Directory & Resource Type 	anim,color, drawable, layout, menu, raw,
* Values - R.array R.integer,R.bool , R.color , R.dimen , R.string, R.style
_________________________________________

## Activity & Fragment
* What is activity? And different phases of the Activity lifecycle.
* What's the difference between a file, a class and an activity in android?
* What is a Fragment? And  lifecycle methods of android Fragment.
* How to "launch modes" and Flags an activity in your application?
* What is the difference between a fragment and an activity?
* What is Dialog in Android?
* What is View in Android?

## Intent & Bundle
* What is intent in Android?
* What is an Explicit Intent?
* What is an Implicit Intent?
* What is a Content Provider?
* What is the difference between Serializable and Parcelable?
* What is the function of an intent filter?
* What is a Sticky Intent?
* What is a PendingIntent?                                               

## Service

   1.	  What is Service in android?
       
           Service is an application component that can perform long-running operations in the background, and it doesn't 
           
           provide a user interface.  
           
           Like -> handle network transactions, play music, perform file I/O etc.


   2.	  What are the different types of Services?
         
           Android provide two types of Services:
           
           •started service->started service is a local service and sort term opration.
           
              it is stop itself stopSelf(). like, network   opration,image download,play music etc.
              
           •bound service-> bound service is remote service and ipc comunication like chat,aap in parchages.


   3.	  Service Lifecycle
   
           • started service=>  call to->  startService() , onCreate(),onStartCommand,service is runing -> onDestroy()

           • bound service=> call to->  bindService(), onCreate(),onBind(),
           
             service is runing ->as par as client requrement -> onUnbind()->onRebind()->onDestroy()

   
   
   4.     Difference between Service vs IntentService.
          
          * Service
                 •work on Main Thread
                 •It is have method stopSelf() and stopService()

          * IntentService
                 •  work on Separate worker thread
                 •  Multiple intents are queued on the same worker thread.
                 •  onHandleIntent()

          
   5.     What is foreground Service?
            
            • Ans:Unless background service it will have more priority , 
              by using setForeGround() method we can make it foreground service.
          
   6.     What is the significance of Sticky Intents in Services?

            * START_STICKY   It is the system will try to re-create our application is kill.
            
            * START_NOT_STICKY  It is the system will not try to re-create our application is kill.
            
            * START_REDELIVER_INTENT  if the Intent is a re-delivery of a previously delivered intent,
              because the service had previously returned

          
      
   7.     What is a JobScheduler?
   
   
   
   
         

## Persist Database

* What is activity? And different phases of the Activity lifecycle.
* What's the difference between a file, a class and an activity in android?
* What is a Fragment? And  lifecycle methods of android Fragment.
* How to "launch modes" and Flags an activity in your application?
______________________________________________

## Android XML Layout

* How would you preserve Activity state during a screen rotation?
* Relativelayout vs Linearlayout.
* How to implement XML namespaces?
* Difference between View.GONE and View.INVISIBLE?
* What is the difference between a regular bitmap and a nine-patch image?
* Tell about the bitmap pool. Mindorks
* What is the difference between ListView and RecyclerView?

