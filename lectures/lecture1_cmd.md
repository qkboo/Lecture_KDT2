
```powershell
(base) C:\Users\daddy>conda create -n Python_basic python=3.10
Collecting package metadata (current_repodata.json): done
Solving environment: done
...
  xz                 pkgs/main/win-64::xz-5.2.10-h8cc25b3_1 None
  zlib               pkgs/main/win-64::zlib-1.2.13-h8cc25b3_0 None


Proceed ([y]/n)? y

# To activate this environment, use
#
#     $ conda activate Python_basic
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```

```
(base) C:\Users\daddy>conda activate Python_basic
(Python_basic) C:\Users\daddy>
```

```
(Python_basic) C:\Users\daddy>conda install jupyterlab pandas
Collecting package metadata (current_repodata.json): done
Solving environment: done

The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    jupyter_client-7.4.9       |  py310haa95532_0         226 KB
    jupyter_core-5.2.0         |  py310haa95532_0         108 KB
    jupyter_server-1.23.4      |  py310haa95532_0         402 KB
    jupyterlab-3.5.3           |  py310haa95532_0         4.0 MB
```    
    
``` 
(Python_basic) C:\Users\daddy>dir pythondata
 C 드라이브의 볼륨에는 이름이 없습니다.
 볼륨 일련 번호: 1AFD-D176

 C:\Users\daddy\pythondata 디렉터리

2023-03-15  오후 02:34    <DIR>          .
2023-03-15  오후 02:34    <DIR>          ..
               0개 파일                   0 바이트
               2개 디렉터리  573,761,609,728 바이트 남음

(Python_basic) C:\Users\daddy>
(Python_basic) C:\Users\daddy>jupyter-lab --no-browser pythondata
[I 2023-03-15 14:48:17.876 ServerApp] jupyterlab | extension was successfully linked.
[I 2023-03-15 14:48:18.420 LabApp] JupyterLab extension loaded from C:\Users\daddy\anaconda3\envs\Python_basic\lib\site-packages\jupyterlab


[I 2023-03-15 14:48:18.436 ServerApp] nbclassic | extension was successfully loaded.
[I 2023-03-15 14:48:18.437 ServerApp] Serving notebooks from local directory: C:\Users\daddy\pythondata
[I 2023-03-15 14:48:18.437 ServerApp] Jupyter Server 1.23.4 is running at:
[I 2023-03-15 14:48:18.437 ServerApp] http://localhost:8888/lab?token=779857126089d4abca53d8fcf524651d0057c0ba5ee108ed
[I 2023-03-15 14:48:18.438 ServerApp]  or http://127.0.0.1:8888/lab?token=779857126089d4abca53d8fcf524651d0057c0ba5ee108ed
[I 2023-03-15 14:48:18.438 ServerApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 2023-03-15 14:48:18.453 ServerApp]

    To access the server, open this file in a browser:
        file:///C:/Users/daddy/AppData/Roaming/jupyter/runtime/jpserver-31124-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/lab?token=779857126089d4abca53d8fcf524651d0057c0ba5ee108ed
     or http://127.0.0.1:8888/lab?token=779857126089d4abca53d8fcf524651d0057c0ba5ee108ed
[I 2023-03-15 14:50:28.464 ServerApp] Interrupted...
^C
(Python_basic) C:\Users\daddy>
```
