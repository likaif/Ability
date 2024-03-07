# STL
## namespace std
### class
1. array
    - 与原生数组类似，定长，栈内存,[和vector区别详情](https://blog.csdn.net/BTChioa/article/details/134960503)

### function
1. fill
    - Assigns the given value to the elements in the range [first, last)，[详情](https://en.cppreference.com/w/cpp/algorithm/fill)
        ```C++
        template< class ForwardIt, class T >
        void fill( ForwardIt first, ForwardIt last, const T& value );
        ```



# Third Parties
## [Eigen](http://eigen.tuxfamily.org/dox/index.html)
## [OpenCV](https://docs.opencv.org/3.4/index.html)
### class
#### cv::Mat
> The Basic Image Container

### function
#### cv::cvtColor
```C++
auto data = cv::imread(path);
cv::cvtColor(data, data, cv::COLOR_RGB2BGR);
```
