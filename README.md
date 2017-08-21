<!-- README.md is generated from README.Rmd. Please edit that file -->
adsample
========

[![Travis-CI Build Status](https://travis-ci.org/kuperov/adsample.svg?branch=master)](https://travis-ci.org/kuperov/adsample) [![Coverage Status](https://img.shields.io/codecov/c/github/kuperov/adsample/master.svg)](https://codecov.io/github/kuperov/adsample?branch=master)

This package implements the adaptive rejection sampling described by Gilks & Wild (1992). It is implemented in C++ and provides a convenient symbolic differentiation tool and diagnostic graphs.

The algorithm can sample from any univariate log concave densities. This is a large number of densities (especially if you allow minor reparameterizations) but is not all of them. See the paper!
