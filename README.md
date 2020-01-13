# filesys<!-- omit in toc -->

## Table of contents<!-- omit in toc -->

- [Introduction](#introduction)
- [Problem definition](#problem-definition)
- [Objectives](#objectives)
	- [Recursive copy](#recursive-copy)
	- [Update (don't overwrite newer files or delete anything)](#update-dont-overwrite-newer-files-or-delete-anything)
	- [Mirror](#mirror)
- [Not objectives](#not-objectives)
- [Notes](#notes)
- [Appendix](#appendix)

## Introduction

Many a sysadmin or power user has desired to use the power of rsync (with secure, differential, checksum-sure, restartable, network-efficient copies), but has been frustrated that a simple file rename or move can completely break it, in terms of those benefits.

This script is the result of a search to bridge those two problem domains, and trying virtually every open-source project under the sun to do so. (Including syncthing, rclone, and countless small projects like this.)

Ursync is based on a brilliant idea first [documented by Vláďa Macek in 2012](https://lincolnloop.com/blog/detecting-file-moves-renames-rsync/), then put into code by Daniele Paroli in a script called [hrsync](https://github.com/dparoli/hrsync).

This script expands on those ideas.

## Problem definition

## Objectives

### Recursive copy

### Update (don't overwrite newer files or delete anything)

### Mirror

## Not objectives

## To-do

- [ ] Finish functionality
- [ ] Remove unused boilerplate code

## Notes

## Appendix
