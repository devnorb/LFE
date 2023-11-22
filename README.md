# LFE
LFE, short for lua function extender, is a project that aims to give more function support to executors which have less functions.

## added synapse cross compatibility
note: if the program <strong>cannot</strong> find the c type function, it will use the lua implemented function.\
it tries to find the c types first because c types better and prob won't break unlike some lua functions.

<strong> ! SCRIPTS MAY OR MAY NOT WORK WITH THIS. ! </strong>

# Added Functions:

<details open>
<summary>Functions</summary>
<br>
information
getscripts
getmodules
newcclosure
islclosure
newlclosure
hookfunction
replaceclosure
getthreadidentity
getexecutioncontext
getmodulescripts
dumpstring
quickload
getthread
isvalidlevel
isluau
firetouchinterest
clonefunction
isrbxactive
getnilinstances
getinstances
getcustomasset
ishiddenproperty
isreadonly
getpropvalue
setpropvalue
getsenv
getloadedmodules
hookfunction
getmenv
isrobloxscript
getspecialinfo
hookmetamethod
require
getallthreads
setsimulationradius
getcallingscript
getrunningscripts
getcurrentline
defersignal
isscriptable
setscriptable
firesignal
fireproximityprompt
getscripthash
HttpGet
</details>

i just realized file library no work >:C fuck
<details>
<summary>Bit / Bit32 Library</summary>
i'm too lazy to write this out :p
basically most of the bit functions
</details>

<details open>
<summary>Debug Library</summary>
<br>
-[ (debug.*) ]-
debug.dumpheap
debug.getconstants
debug.getproto
debug.setmemorycategory
debug.profilebegin
debug.loadmodule
debug.traceback
debug.getupvalues
debug.getupvalue
debug.getmemorycategory
debug.resetmemorycategory
debug.setupvalue
debug.getconstant
debug.getregistry
debug.setmetatable
debug.profileend
debug.dumprefs
debug.getinfo
debug.getprotos
debug.setconstant
debug.getmetatable
debug.info
</details>
