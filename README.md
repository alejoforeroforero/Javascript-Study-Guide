# Javascript-Study-Guide
Javascript Study Guide

- Object destructuring
     
      const {id, info} = req.body; //get differentes properties from a json obj and assign the value to the variables declare
      
- Array Filter:

      const cards = DUMMY_CARDS.filter(card=>{
          return card.creator === userId;
      })
      
      const cards = DUMMY_CARDS.filter(card => card.creator === userId); //short way
