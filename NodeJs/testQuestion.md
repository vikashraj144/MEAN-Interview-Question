> which is the most commonly used event in eventEmitter
> start , data , click, focus
> which of the following type of stream can be used for both read and write operation in node js
> duplex,transform,piping,stream reader
> node js callback function is similar to which type of funtion in javascript
> asynchronous,syncronous,thread,multi thread

> which of the following methods returns object with a build-in communication channel in addition to having all the methods
> in a normal child process instance
> watch(),fork(),set(),connect()

> what is the operation in put request, which is used to make RESTFUL request
> insert data ,update ,get,move

> which is the following ways is not used for creating the buffer in a project
> var buff = new Buffer(4)
> var buff = new Buffer([20,30])
> var buff = new Buffer('example','utf-8')
> var buff = new Buffer('example','base-64')

> what code can be used to copy an ASCII string into a buffer,one byte at a time ?

> which is the following module is not used for tetsing environment in node js
> mocha,jasmine,bower,vows

> what could be the possible cause for the error,ETIMEDOUT Operation time out
> port is not opened on destination system
> proces execution time is not set
> request was not completed in time
> firewall rules deny the connection

> what will be the output
> function async(arg,callback){

    console.log('do something with \''+arg+'\',');
    settimeout(function(){callback(arg*2),1000})

}

var items = [1,2,3,4,5,6];
var result =[];
function series(item) {
if(item){
async(item,function(result){
result.push(result);
return series(items.shift());
})
}
}

series(items.shift);
