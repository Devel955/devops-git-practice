#!/bin/bash


# 📘 Day 23 – Understanding Git Branches

## 1. What is a branch in Git?
A branch is an independent line of development. It points to a series of commits and lets you work without affecting the main branch.

## 2. Why do we use branches instead of committing everything to main?
Branches keep main stable and allow safe feature development, bug fixes, and parallel work. This avoids breaking production code and keeps history clean.

## 3. What is HEAD in Git?
HEAD is a pointer to your current location in Git—usually the current branch’s latest commit. When you switch branches, HEAD moves with it.

## 4. What happens to your files when you switch branches?
Git updates your working directory to match the branch you switched to. Files can change/appear/disappear based on commits in that branch. If you have conflicting uncommitted changes, Git may block the switch.
