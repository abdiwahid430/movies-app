import React from 'react';
import MovieCard from './MovieCard';

const MovieList = ({ movies }) => {
  return (
    <div style={{ display: 'flex', flexWrap: 'wrap' }}>
      {movies.map((movie, index) => (
        <MovieCard 
          key={index} 
          title={movie.title} 
          description={movie.description} 
          posterURL={movie.posterURL} 
          rating={movie.rating} 
        />
      ))}
    </div>
  );
};

export default MovieList;

import React from 'react';

const Filter = ({ titleFilter, rateFilter, onTitleChange, onRateChange }) => {
  return (
    <div style={{ marginBottom: '16px' }}>
      <input 
        type="text" 
        placeholder="Filter by title" 
        value={titleFilter} 
        onChange={onTitleChange} 
      />
      <input 
        type="number" 
        placeholder="Filter by rating" 
        value={rateFilter} 
        onChange={onRateChange} 
      />
    </div>
  );
};

export default Filter;

import React from 'react';

const Filter = ({ titleFilter, rateFilter, onTitleChange, onRateChange }) => {
  return (
    <div style={{ marginBottom: '16px' }}>
      <input 
        type="text" 
        placeholder="Filter by title" 
        value={titleFilter} 
        onChange={onTitleChange} 
      />
      <input 
        type="number" 
        placeholder="Filter by rating" 
        value={rateFilter} 
        onChange={onRateChange} 
      />
    </div>
  );
};

export default Filter;
import React from 'react';

const Filter = ({ titleFilter, rateFilter, onTitleChange, onRateChange }) => {
  return (
    <div style={{ marginBottom: '16px' }}>
      <input 
        type="text" 
        placeholder="Filter by title" 
        value={titleFilter} 
        onChange={onTitleChange} 
      />
      <input 
        type="number" 
        placeholder="Filter by rating" 
        value={rateFilter} 
        onChange={onRateChange} 
      />
    </div>
  );
};

export default Filter;
