.. AutoKernel documentation master file, created by
   sphinx-quickstart on Wed Mar 11 12:03:10 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to AutoKernel Docs!
===================================


.. toctree::
  :maxdepth: 1
  :caption: 简介
  :name: sec-introduction

  introduction/architecture
  introduction/support_hardware
  introduction/support_op


.. toctree::
  :maxdepth: 1
  :caption: 快速开始
  :name: sec-quick-start

  quick_start/install
  quick_start/docker
  quick_start/tengine
  quick_start/halide
  quick_start/autokernel_plugin_tengine
  quick_start/gemm
  quick_start/cv_op
  quick_start/autosearch



.. toctree::
  :maxdepth: 1
  :caption: 多后端示例
  :name: sec-demo_guides

  demo_guides/arm64_cpu
  demo_guides/x86_cpu
  demo_guides/opencl
  demo_guides/cuda_matmul/cuda

.. toctree::
  :maxdepth: 1
  :caption: 教程Tutorials
  :name: sec-source-compile

  tutorials/01_AutoKernel开发环境快速入门   
  tutorials/02_Tengine快速入门          
  tutorials/03_Halide初体验             
  tutorials/04_AutoKernel插件指南             
  tutorials/05_Halide调度策略Schedule                
  tutorials/06_GEMM调度策略优化指南           
  


.. toctree::
  :maxdepth: 1
  :caption: 博文Blog

  blog/autokernel_optimize_gemm_over_200_times_faster
  blog/ai_compiler_overview

